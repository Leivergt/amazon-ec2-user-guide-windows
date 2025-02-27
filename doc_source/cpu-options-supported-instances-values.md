# CPU cores and threads per CPU core per instance type<a name="cpu-options-supported-instances-values"></a>

The following tables list the instance types that support specifying CPU options\.

**Topics**
+ [Accelerated computing instances](#cpu-options-accelerated)
+ [Compute optimized instances](#cpu-options-compute-optimized)
+ [General purpose instances](#cpu-options-gen-purpose)
+ [Memory optimized instances](#cpu-options-mem-optimized)
+ [Storage optimized instances](#cpu-options-storage-optimized)

## Accelerated computing instances<a name="cpu-options-accelerated"></a>


| Instance type | Default vCPUs | Default CPU cores | Default threads per core | Valid CPU cores | Valid threads per core | 
| --- | --- | --- | --- | --- | --- | 
| f1\.2xlarge | 8 | 4 | 2 | 1 to 4 | 1, 2 | 
| f1\.4xlarge | 16 | 8 | 2 | 1 to 8 | 1, 2 | 
| f1\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| g3\.4xlarge | 16 | 8 | 2 | 1 to 8 | 1, 2 | 
| g3\.8xlarge | 32 | 16 | 2 | 1 to 16 | 1, 2 | 
| g3\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| g3s\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| g4ad\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| g4ad\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| g4ad\.4xlarge | 16 | 8 | 2 | 2, 4, 8 | 1, 2 | 
| g4ad\.8xlarge | 32 | 16 | 2 | 2, 4, 8, 16 | 1, 2 | 
| g4ad\.16xlarge | 64 | 32 | 2 | 2, 4, 8, 16, 32 | 1, 2 | 
| g4dn\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| g4dn\.2xlarge | 8 | 4 | 2 | 1 to 4 | 1, 2 | 
| g4dn\.4xlarge | 16 | 8 | 2 | 1 to 8 | 1, 2 | 
| g4dn\.8xlarge | 32 | 16 | 2 | 1 to 16 | 1, 2 | 
| g4dn\.12xlarge | 48 | 24 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| g4dn\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| p2\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| p2\.8xlarge | 32 | 16 | 2 | 1 to 16 | 1, 2 | 
| p2\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| p3\.2xlarge | 8 | 4 | 2 | 1 to 4 | 1, 2 | 
| p3\.8xlarge | 32 | 16 | 2 | 1 to 16 | 1, 2 | 
| p3\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| p3dn\.24xlarge | 96 | 48 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 

## Compute optimized instances<a name="cpu-options-compute-optimized"></a>


| Instance type | Default vCPUs | Default CPU cores | Default threads per core | Valid CPU cores | Valid threads per core | 
| --- | --- | --- | --- | --- | --- | 
| c4\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| c4\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| c4\.2xlarge | 8 | 4 | 2 | 1 to 4 | 1, 2 | 
| c4\.4xlarge | 16 | 8 | 2 | 1 to 8 | 1, 2 | 
| c4\.8xlarge | 36 | 18 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18 | 1, 2 | 
| c5\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| c5\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| c5\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| c5\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| c5\.9xlarge | 36 | 18 | 2 | 4, 6, 8, 10, 12, 14, 16, 18 | 1, 2 | 
| c5\.12xlarge | 48 | 24 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| c5\.18xlarge | 72 | 36 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36 | 1, 2 | 
| c5\.24xlarge | 96 | 48 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| c5a\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| c5a\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| c5a\.2xlarge | 8 | 4 | 2 | 1 to 4 | 1, 2 | 
| c5a\.4xlarge | 16 | 8 | 2 | 1, 2, 3, 4, 8 | 1, 2 | 
| c5a\.8xlarge | 32 | 16 | 2 | 1, 2, 3, 4, 8, 12, 16 | 1, 2 | 
| c5a\.12xlarge | 48 | 24 | 2 | 1, 2, 3, 4, 8, 12, 16, 20, 24 | 1, 2 | 
| c5a\.16xlarge | 64 | 32 | 2 | 1, 2, 3, 4, 8, 12, 16, 20, 24, 28, 32 | 1, 2 | 
| c5a\.24xlarge | 96 | 48 | 2 | 1, 2, 3, 4, 8, 12, 16, 20, 24, 28, 32, 36, 40, 44, 48 | 1, 2 | 
| c5ad\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| c5ad\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| c5ad\.2xlarge | 8 | 4 | 2 | 1 to 4 | 1, 2 | 
| c5ad\.4xlarge | 16 | 8 | 2 | 1, 2, 3, 4, 8 | 1, 2 | 
| c5ad\.8xlarge | 32 | 16 | 2 | 1, 2, 3, 4, 8, 12, 16 | 1, 2 | 
| c5ad\.12xlarge | 48 | 24 | 2 | 1, 2, 3, 4, 8, 12, 16, 20, 24 | 1, 2 | 
| c5ad\.16xlarge | 64 | 32 | 2 | 1, 2, 3, 4, 8, 12, 16, 20, 24, 28, 32 | 1, 2 | 
| c5ad\.24xlarge | 96 | 48 | 2 | 1, 2, 3, 4, 8, 12, 16, 20, 24, 28, 32, 36, 40, 44, 48 | 1, 2 | 
| c5d\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| c5d\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| c5d\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| c5d\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| c5d\.9xlarge | 36 | 18 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18 | 1, 2 | 
| c5d\.12xlarge | 48 | 24 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| c5d\.18xlarge | 72 | 36 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36 | 1, 2 | 
| c5d\.24xlarge | 96 | 48 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| c5n\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| c5n\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| c5n\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| c5n\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| c5n\.9xlarge | 36 | 18 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18 | 1, 2 | 
| c5n\.18xlarge | 72 | 36 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36 | 1, 2 | 
| c6a\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| c6a\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| c6a\.2xlarge | 8 | 4 | 2 | 1 to 4 | 1, 2 | 
| c6a\.4xlarge | 16 | 8 | 2 | 1 to 8 | 1, 2 | 
| c6a\.8xlarge | 32 | 16 | 2 | 1, 2, 3, 4, 5, 6, 7, 8, 16  | 1, 2 | 
| c6a\.12xlarge | 48 | 24 | 2 | 1, 2, 3, 4, 5, 6, 7, 8, 16, 24  | 1, 2 | 
| c6a\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 32 | 1, 2 | 
| c6a\.24xlarge | 96 | 48 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 32, 48 | 1, 2 | 
| c6a\.32xlarge | 128 | 64 | 2 | 4, 8, 12, 16, 20, 24, 28, 32, 64 | 1, 2 | 
| c6a\.48xlarge | 192 | 96 | 2 | 4, 8, 12, 16, 20, 24, 28, 32, 64, 96 | 1, 2 | 
| c6i\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| c6i\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| c6i\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| c6i\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| c6i\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| c6i\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| c6i\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| c6i\.24xlarge | 96 | 48 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| c6i\.32xlarge | 128 | 64 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48, 50, 52, 54, 56, 58, 60, 62, 64 | 1, 2 | 
| c6id\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| c6id\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| c6id\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| c6id\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| c6id\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| c6id\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| c6id\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| c6id\.24xlarge | 96 | 48 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| c6id\.32xlarge | 128 | 64 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48, 50, 52, 54, 56, 58, 60, 62, 64 | 1, 2 | 

## General purpose instances<a name="cpu-options-gen-purpose"></a>


| Instance type | Default vCPUs | Default CPU cores | Default threads per core | Valid CPU cores | Valid threads per core | 
| --- | --- | --- | --- | --- | --- | 
| m4\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| m4\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| m4\.2xlarge | 8 | 4 | 2 | 1 to 4 | 1, 2 | 
| m4\.4xlarge | 16 | 8 | 2 | 1 to 8 | 1, 2 | 
| m4\.10xlarge | 40 | 20 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20 | 1, 2 | 
| m4\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| m5\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| m5\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| m5\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| m5\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| m5\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| m5\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| m5\.16xlarge | 64 | 32 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| m5\.24xlarge | 96 | 48 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| m5a\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| m5a\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| m5a\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| m5a\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| m5a\.8xlarge | 32 | 16 | 2 | 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| m5a\.12xlarge | 48 | 24 | 2 | 6, 12, 18, 24 | 1, 2 | 
| m5a\.16xlarge | 64 | 32 | 2 | 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| m5a\.24xlarge | 96 | 48 | 2 | 12, 18, 24, 36, 48 | 1, 2 | 
| m5ad\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| m5ad\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| m5ad\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| m5ad\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| m5ad\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| m5ad\.12xlarge | 48 | 24 | 2 | 6, 12, 18, 24 | 1, 2 | 
| m5ad\.16xlarge | 64 | 32 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| m5ad\.24xlarge | 96 | 48 | 2 | 12, 18, 24, 36, 48 | 1, 2 | 
| m5d\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| m5d\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| m5d\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| m5d\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| m5d\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| m5d\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| m5d\.16xlarge | 64 | 32 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| m5d\.24xlarge | 96 | 48 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| m5dn\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| m5dn\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| m5dn\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| m5dn\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| m5dn\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| m5dn\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| m5dn\.16xlarge | 64 | 32 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| m5dn\.24xlarge | 96 | 48 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| m5n\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| m5n\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| m5n\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| m5n\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| m5n\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| m5n\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| m5n\.16xlarge | 64 | 32 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| m5n\.24xlarge | 96 | 48 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| m5zn\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| m5zn\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| m5zn\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| m5zn\.3xlarge | 12 | 6 | 2 | 2, 4, 6 | 1, 2 | 
| m5zn\.6xlarge | 24 | 12 | 2 | 2, 4, 6, 8, 10, 12 | 1, 2 | 
| m5zn\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| m6a\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| m6a\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| m6a\.2xlarge | 8 | 4 | 2 | 1 to 4 | 1, 2 | 
| m6a\.4xlarge | 16 | 8 | 2 | 1 to 8 | 1, 2 | 
| m6a\.8xlarge | 32 | 16 | 2 | 1, 2, 3, 4, 5, 6, 7, 8, 16  | 1, 2 | 
| m6a\.12xlarge | 48 | 24 | 2 | 1, 2, 3, 4, 5, 6, 7, 8, 16, 24  | 1, 2 | 
| m6a\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 32 | 1, 2 | 
| m6a\.24xlarge | 96 | 48 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 32, 48 | 1, 2 | 
| m6a\.32xlarge | 128 | 64 | 2 | 4, 8, 12, 16, 20, 24, 28, 32, 64 | 1, 2 | 
| m6a\.48xlarge | 192 | 96 | 2 | 4, 8, 12, 16, 20, 24, 28, 32, 64, 96 | 1, 2 | 
| m6i\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| m6i\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| m6i\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| m6i\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| m6i\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| m6i\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| m6i\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| m6i\.24xlarge | 96 | 48 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| m6i\.32xlarge | 128 | 64 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48, 50, 52, 54, 56, 58, 60, 62, 64 | 1, 2 | 
| m6id\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| m6id\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| m6id\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| m6id\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| m6id\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| m6id\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| m6id\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| m6id\.24xlarge | 96 | 48 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| m6id\.32xlarge | 128 | 64 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48, 50, 52, 54, 56, 58, 60, 62, 64 | 1, 2 | 
| t3\.nano | 2 | 1 | 2 | 1 | 1, 2 | 
| t3\.micro | 2 | 1 | 2 | 1 | 1, 2 | 
| t3\.small | 2 | 1 | 2 | 1 | 1, 2 | 
| t3\.medium | 2 | 1 | 2 | 1 | 1, 2 | 
| t3\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| t3\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| t3\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| t3a\.nano | 2 | 1 | 2 | 1 | 1, 2 | 
| t3a\.micro | 2 | 1 | 2 | 1 | 1, 2 | 
| t3a\.small | 2 | 1 | 2 | 1 | 1, 2 | 
| t3a\.medium | 2 | 1 | 2 | 1 | 1, 2 | 
| t3a\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| t3a\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| t3a\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 

## Memory optimized instances<a name="cpu-options-mem-optimized"></a>


| Instance type | Default vCPUs | Default CPU cores | Default threads per core | Valid CPU cores | Valid threads per core | 
| --- | --- | --- | --- | --- | --- | 
| r4\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| r4\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| r4\.2xlarge | 8 | 4 | 2 | 1 to 4 | 1, 2 | 
| r4\.4xlarge | 16 | 8 | 2 | 1 to 8 | 1, 2 | 
| r4\.8xlarge | 32 | 16 | 2 | 1 to 16 | 1, 2 | 
| r4\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| r5\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| r5\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| r5\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| r5\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| r5\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| r5\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| r5\.16xlarge | 64 | 32 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| r5\.24xlarge | 96 | 48 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| r5a\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| r5a\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| r5a\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| r5a\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| r5a\.8xlarge | 32 | 16 | 2 | 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| r5a\.12xlarge | 48 | 24 | 2 | 6, 12, 18, 24 | 1, 2 | 
| r5a\.16xlarge | 64 | 32 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| r5a\.24xlarge | 96 | 48 | 2 | 12, 18, 24, 36, 48 | 1, 2 | 
| r5ad\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| r5ad\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| r5ad\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| r5ad\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| r5ad\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| r5ad\.12xlarge | 48 | 24 | 2 | 6, 12, 18, 24 | 1, 2 | 
| r5ad\.16xlarge | 64 | 32 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| r5ad\.24xlarge | 96 | 48 | 2 | 12, 18, 24, 36, 48 | 1, 2 | 
| r5b\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| r5b\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| r5b\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| r5b\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| r5b\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| r5b\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| r5b\.16xlarge | 64 | 32 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| r5b\.24xlarge | 96 | 48 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| r5d\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| r5d\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| r5d\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| r5d\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| r5d\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| r5d\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| r5d\.16xlarge | 64 | 32 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| r5d\.24xlarge | 96 | 48 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| r5dn\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| r5dn\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| r5dn\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| r5dn\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| r5dn\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| r5dn\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| r5dn\.16xlarge | 64 | 32 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| r5dn\.24xlarge | 96 | 48 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| r5n\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| r5n\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| r5n\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| r5n\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| r5n\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| r5n\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| r5n\.16xlarge | 64 | 32 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| r5n\.24xlarge | 96 | 48 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| r6a\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| r6a\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| r6a\.2xlarge | 8 | 4 | 2 | 1 to 4 | 1, 2 | 
| r6a\.4xlarge | 16 | 8 | 2 | 1 to 8 | 1, 2 | 
| r6a\.8xlarge | 32 | 16 | 2 | 1, 2, 3, 4, 5, 6, 7, 8, 16  | 1, 2 | 
| r6a\.12xlarge | 48 | 24 | 2 | 1, 2, 3, 4, 5, 6, 7, 8, 16, 24  | 1, 2 | 
| r6a\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 32 | 1, 2 | 
| r6a\.24xlarge | 96 | 48 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 32, 48 | 1, 2 | 
| r6a\.32xlarge | 128 | 64 | 2 | 4, 8, 12, 16, 20, 24, 28, 32, 64 | 1, 2 | 
| r6a\.48xlarge | 192 | 96 | 2 | 4, 8, 12, 16, 20, 24, 28, 32, 64, 96 | 1, 2 | 
| r6i\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| r6i\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| r6i\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| r6i\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| r6i\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| r6i\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| r6i\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| r6i\.24xlarge | 96 | 48 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| r6i\.32xlarge | 128 | 64 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48, 50, 52, 54, 56, 58, 60, 62, 64 | 1, 2 | 
| r6id\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| r6id\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| r6id\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| r6id\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| r6id\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| r6id\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| r6id\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| r6id\.24xlarge | 96 | 48 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| r6id\.32xlarge | 128 | 64 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48, 50, 52, 54, 56, 58, 60, 62, 64 | 1, 2 | 
| u\-3tb1\.56xlarge | 224 | 112 | 2 | 4, 8, 12, 16, 20, 24, 28, 32, 36, 40, 44, 48, 52, 56, 60, 64, 68, 72, 76, 80, 84, 88, 92, 96, 100, 104, 108, 112 | 1, 2 | 
| u\-6tb1\.56xlarge | 224 | 224 | 1 | 8, 16, 24, 32, 40, 48, 56, 64, 72, 80, 88, 96, 104, 112, 120, 128, 136, 144, 152, 160, 168, 176, 184, 192, 200, 208, 216, 224 | 1 | 
| u\-6tb1\.112xlarge | 448 | 224 | 2 | 8, 16, 24, 32, 40, 48, 56, 64, 72, 80, 88, 96, 104, 112, 120, 128, 136, 144, 152, 160, 168, 176, 184, 192, 200, 208, 216, 224 | 1, 2 | 
| u\-9tb1\.112xlarge | 448 | 224 | 2 | 8, 16, 24, 32, 40, 48, 56, 64, 72, 80, 88, 96, 104, 112, 120, 128, 136, 144, 152, 160, 168, 176, 184, 192, 200, 208, 216, 224 | 1, 2 | 
| u\-12tb1\.112xlarge | 448 | 224 | 2 | 8, 16, 24, 32, 40, 48, 56, 64, 72, 80, 88, 96, 104, 112, 120, 128, 136, 144, 152, 160, 168, 176, 184, 192, 200, 208, 216, 224 | 1, 2 | 
| x1\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| x1\.32xlarge | 128 | 64 | 2 | 4, 8, 12, 16, 20, 24, 28, 32, 36, 40, 44, 48, 52, 56, 60, 64 | 1, 2 | 
| x1e\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| x1e\.2xlarge | 8 | 4 | 2 | 1 to 4 | 1, 2 | 
| x1e\.4xlarge | 16 | 8 | 2 | 1 to 8 | 1, 2 | 
| x1e\.8xlarge | 32 | 16 | 2 | 1 to 16 | 1, 2 | 
| x1e\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| x1e\.32xlarge | 128 | 64 | 2 | 4, 8, 12, 16, 20, 24, 28, 32, 36, 40, 44, 48, 52, 56, 60, 64 | 1, 2 | 
| x2idn\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| x2idn\.24xlarge | 96 | 48 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| x2idn\.32xlarge | 128 | 64 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48, 50, 52, 54, 56, 58, 60, 62, 64 | 1, 2 | 
| x2iedn\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| x2iedn\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| x2iedn\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| x2iedn\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| x2iedn\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| x2iedn\.24xlarge | 96 | 48 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| x2iedn\.32xlarge | 128 | 64 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48, 50, 52, 54, 56, 58, 60, 62, 64 | 1, 2 | 
| x2iezn\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| x2iezn\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| x2iezn\.6xlarge | 24 | 12 | 2 | 2, 4, 6, 8, 10, 12 | 1, 2 | 
| x2iezn\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| x2iezn\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| z1d\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| z1d\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| z1d\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| z1d\.3xlarge | 12 | 6 | 2 | 2, 4, 6 | 1, 2 | 
| z1d\.6xlarge | 24 | 12 | 2 | 2, 4, 6, 8, 10, 12 | 1, 2 | 
| z1d\.12xlarge | 48 | 24 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 

## Storage optimized instances<a name="cpu-options-storage-optimized"></a>


| Instance type | Default vCPUs | Default CPU cores | Default threads per core | Valid CPU cores | Valid threads per core | 
| --- | --- | --- | --- | --- | --- | 
| d2\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| d2\.2xlarge | 8 | 4 | 2 | 1 to 4 | 1, 2 | 
| d2\.4xlarge | 16 | 8 | 2 | 1 to 8 | 1, 2 | 
| d2\.8xlarge | 36 | 18 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18 | 1, 2 | 
| d3\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| d3\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| d3\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| d3\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| d3en\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| d3en\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| d3en\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| d3en\.4xlarge | 16 | 8 | 2 | 2, 4, 6, 8 | 1, 2 | 
| d3en\.6xlarge | 24 | 12 | 2 | 2, 4, 6, 8, 10, 12 | 1, 2 | 
| d3en\.8xlarge | 32 | 16 | 2 | 2, 4, 6, 8, 10, 12, 14, 16 | 1, 2 | 
| d3en\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| h1\.2xlarge | 8 | 4 | 2 | 1 to 4 | 1, 2 | 
| h1\.4xlarge | 16 | 8 | 2 | 1 to 8 | 1, 2 | 
| h1\.8xlarge | 32 | 16 | 2 | 1 to 16 | 1, 2 | 
| h1\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| i3\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| i3\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| i3\.2xlarge | 8 | 4 | 2 | 1 to 4 | 1, 2 | 
| i3\.4xlarge | 16 | 8 | 2 | 1 to 8 | 1, 2 | 
| i3\.8xlarge | 32 | 16 | 2 | 1 to 16 | 1, 2 | 
| i3\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| i3en\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| i3en\.xlarge | 4 | 2 | 2 | 2 | 1, 2 | 
| i3en\.2xlarge | 8 | 4 | 2 | 2, 4 | 1, 2 | 
| i3en\.3xlarge | 12 | 6 | 2 | 2, 4, 6 | 1, 2 | 
| i3en\.6xlarge | 24 | 12 | 2 | 2, 4, 6, 8, 10, 12 | 1, 2 | 
| i3en\.12xlarge | 48 | 24 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24 | 1, 2 | 
| i3en\.24xlarge | 96 | 48 | 2 | 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48 | 1, 2 | 
| i4i\.large | 2 | 1 | 2 | 1 | 1, 2 | 
| i4i\.xlarge | 4 | 2 | 2 | 1, 2 | 1, 2 | 
| i4i\.2xlarge | 8 | 4 | 2 | 1 to 4 | 1, 2 | 
| i4i\.4xlarge | 16 | 8 | 2 | 1 to 8 | 1, 2 | 
| i4i\.8xlarge | 32 | 16 | 2 | 1 to 16 | 1, 2 | 
| i4i\.16xlarge | 64 | 32 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32 | 1, 2 | 
| i4i\.32xlarge | 128 | 64 | 2 | 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48, 50, 52, 54, 56, 58, 60, 62, 64 | 1, 2 | 