# Data Cleaning & Preprocessing – Medical Appointment Dataset

## Dataset Details:

Original rows: 110,527

Columns: 14

### Cleaning Steps Performed:

Removed duplicate records (1 row dropped).

Fixed column names to lowercase and replaced spaces with underscores.

Corrected typos: hipertension → hypertension, handcap → handicap.

Converted scheduledday and appointmentday to datetime format.

Removed rows with invalid ages (negative values).

Standardized text values in no-show column (Yes/No).

Verified datatypes (age = integer, dates = datetime).

### Final Dataset:

Rows after cleaning: 110,526

Columns: 14
