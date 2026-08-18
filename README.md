INSERT INTO students (
    first_name,
    last_name,
    student_id,
    email,
    date_of_birth,
    contact_number,
    enrollment_date,
    profile_image
)
VALUES
    ('William', 'Niyonzima', 'ST051', 'william.niyonzima@example.com', '2002-03-12', '0789123451', '2026-01-15', NULL),
    ('Emma', 'Uwamahoro', 'ST052', 'emma.uwamahoro@example.com', '2003-07-08', '0799234562', '2026-01-15', NULL),
    ('Alexandre', 'Mugabo', 'ST053', 'alexandre.mugabo@example.com', '2001-10-24', '0729345673', '2026-01-15', NULL),
    ('Lydia', 'Mukamana', 'ST054', 'lydia.mukamana@example.com', '2004-04-16', '0739456784', '2026-01-15', NULL),
    ('Martin', 'Tuyisenge', 'ST055', 'martin.tuyisenge@example.com', '2002-08-29', '0789567895', '2026-01-15', NULL),
    ('Stella', 'Ingabire', 'ST056', 'stella.ingabire@example.com', '2003-12-13', '0799678906', '2026-01-15', NULL),
    ('Benjamin', 'Ndayisenga', 'ST057', 'benjamin.ndayisenga@example.com', '2001-05-07', '0729789017', '2026-01-15', NULL),
    ('Gloria', 'Uwineza', 'ST058', 'gloria.uwineza@example.com', '2004-09-22', '0739890128', '2026-01-15', NULL),
    ('Henry', 'Nsengiyumva', 'ST059', 'henry.nsengiyumva@example.com', '2002-11-19', '0788901239', '2026-01-15', NULL),
    ('Alice', 'Munyakazi', 'ST060', 'alice.munyakazi@example.com', '2003-01-26', '0798012340', '2026-01-15', NULL);

SELECT *
FROM students
WHERE student_id BETWEEN 'ST051' AND 'ST060'
ORDER BY student_id;
