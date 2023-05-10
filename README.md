# Healthcare-Management-System
The Healthcare Management System (HMS) is a application designed for hospitals, clinics, and healthcare centers to efficiently manage patient data, medical records, prescriptions, and various departments within the healthcare facility. This system provides a comprehensive solution to store, retrieve, and manage patient data and other vital information.

The HMS application is built using the sqlite3 module, which ensures secure and efficient database management. Additionally, the application uses streamlit to create an intuitive user interface, and pandas library is utilized to simplify data manipulation and analysis.


  ```
# configuration file containing confidential credentials
# user authentication password is used to login to the application
# edit mode password is required to add, delete or update any patient, doctor or department record 
# doctor/medical lab scientist (MLS) access code is given only to the doctors and MLSs, using which they can add, delete or update any prescription or medical test record

password = '<user_authentication_password>'                               # e.g. password = '1234'
database_name = '<current_database_name>'                                 # e.g. database_name = 'database_1A'
edit_mode_password = '<edit_mode_password>'                               # e.g. edit_mode_password = 'edit'
dr_mls_access_code = '<doctor_or_medical_lab_scientist_access_code>'      # e.g. dr_mls_access_code = 'auth'
  ```
  
