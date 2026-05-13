IF OBJECT_ID('silver.CRM_cust_info', 'U') IS NOT NULL
DROP TABLE silver.CRM_cust_info;
create table Silver.CRM_cust_info(
   Cst_id INT,
   CST_key NVARCHAR(50),
   CST_FIRSTNAME NVARCHAR(50),
   CST_LASTNAME NVARCHAR(50),
   CST_Material_status NVARCHAR(50),
   CST_gndr NVARCHAR(50),
   CST_CREAT_DATE date,
   DWH_create_date datetime2 default getdate()
);
IF OBJECT_ID('silver.crm_prd_info', 'U') IS NOT NULL
    DROP TABLE silver.crm_prd_info;

CREATE TABLE silver.crm_prd_info (
    prd_id           INT,
    cat_id           NVARCHAR(50),
    prd_key          NVARCHAR(50),
    prd_nm           NVARCHAR(50),
    prd_cost         INT,
    prd_line         NVARCHAR(50),
    prd_start_dt     DATE,
    prd_end_dt       DATE,
    dwh_create_date  DATETIME2 DEFAULT GETDATE()
);
IF OBJECT_ID('silver.crm_sales_details', 'U') IS NOT NULL
    DROP TABLE silver.crm_sales_details;
CREATE TABLE Silver.crm_sales_details (
    sls_ord_num    NVARCHAR(50),
    sls_prd_key    NVARCHAR(50),
    sls_cust_id    INT,
    sls_order_dt   DATE,
    sls_ship_dt    DATE,
    sls_due_dt     DATE,
    sls_sales      INT,
    sls_quantity   INT,
    sls_price      INT,
   DWH_create_date datetime2 default getdate()
);
IF OBJECT_ID('silver.erp_loc_a101', 'U') IS NOT NULL
    DROP TABLE silver.erp_loc_a101;
CREATE TABLE Silver.erp_loc_a101 (
    cid     NVARCHAR(50),
    cntry   NVARCHAR(50),
   DWH_create_date datetime2 default getdate()
);
IF OBJECT_ID('silver.erp_cust_az12 ', 'U') IS NOT NULL
    DROP TABLE silver.erp_cust_az12 ;
CREATE TABLE Silver.erp_cust_az12 (
    cid     NVARCHAR(50),
    bdate   DATE,
    gen     NVARCHAR(50),
   DWH_create_date datetime2 default getdate()
);
IF OBJECT_ID('silver.erp_px_cat_g1v2  ', 'U') IS NOT NULL
    DROP TABLE silver.erp_px_cat_g1v2 ;
CREATE TABLE Silver.erp_px_cat_g1v2 (
    id            NVARCHAR(50),
    cat           NVARCHAR(50),
    subcat        NVARCHAR(50),
    maintenance   NVARCHAR(50),
   DWH_create_date datetime2 default getdate()
);
