export
`mysqldump -u username -p database_name > data-dump.sql`

import
`mysql -u username -p new_database < data-dump.sql`