Orgaized as like :: SNOWFALKE IS TARGET-DB

</br> DevOps PoC (Database CI/CD Automation) :  GitHub [Repository] à Jenkins [CI/CD Automation] à Liquibase [DB Change Management] à Snowflake
</br> Schema versioning Change Managements
</br> Proc Logic versioning Change Managements
</br> Multiple major/minor releases and deployment use cases
</br> Roll Back Strategy
</br> DB Sync
</br> DB Compare
</br> DB Snapshot and recreate new DV
</br> Deployment Reporting and continues Mentoring


</br> DATABASE REPO STRUCUTURE::

</br> # EnterpriseDataHub
</br> EnterpriseDataHub - Database dbobjects handled all the checkIn/Deployment in snowflake::

</br> --ProjectName:EnterpriseDataHub
</br> --Respoistory:Database
</br> --Branch:Develop
</br> --Folder:Schema

<br>--Subfolders:Database-Object-Types
</br>	SCHEMAS
</br> OBJECTS
</br>	TABLES
</br>	EXTERNAL_TABLES
</br>	VIEWS
</br>	MATERIALIZED_VIEWS
</br>	MASKING_POLICIES
</br>	ROW_ACCESS_POLICIES
</br>	COLUMNS
</br>	FILE_FORMATS
</br>	SEQUENCES
</br>	STAGES
</br>	TAGS
</br>	PIPES
</br>	STREAMS
</br>	TASKS
</br>	USER_FUNCTIONS
</br>	FUNCTIONS
</br>	PROCEDURES
</br>	ADHOC_OTHERS

</br>	--Subfolders:Account-Operations
</br>	PARAMETERS
</br>	CONNECTIONS
</br>	GLOBAL_ACCOUNTS
</br>	REGIONS
</br>	REPLICATION_ACCOUNTS
</br>	REPLICATION_DATABASES
</br>	ADHOC_OTHERS
	
</br>	--Subfolders:Session-User-Operation
</br>	PARAMETERS
</br>	VARIABLES
</br>	TRANSACTIONS
</br>	LOCKS
</br>	ADHOC_OTHERS
