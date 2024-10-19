``` mermaid

 graph TD
    AWS_FSx[AWS FSx Service]:::main
    AWS_FSx --> |Provides| FSx_Windows[FSx for Windows]:::windows
    AWS_FSx --> |Provides| FSx_Lustre[FSx for Lustre]:::lustre
    AWS_FSx --> |Provides| FSx_NetApp[FSx for NetApp ONTAP]:::netapp
    AWS_FSx --> |Provides| FSx_OpenZFS[FSx for OpenZFS]:::openzfs
    
    FSx_Windows --> |Managed| Active_Directory[Active Directory]:::activeDirectory
    FSx_Windows --> |Supports| SMB[Server Message Block]:::smb
    
    FSx_Lustre --> |Optimized for| HPC[High Performance Computing]:::hpc
    FSx_Lustre --> |Supports| S3[Amazon S3 Integration]:::s3

    FSx_NetApp --> |Supports| NFS[Network File System]:::nfs
    FSx_NetApp --> |Supports| SMB[Server Message Block]:::smb
    FSx_NetApp --> |Includes| Data_Protection[Data Protection]:::dataProtection

    FSx_OpenZFS --> |Supports| NFS[Network File System]:::nfs
    FSx_OpenZFS --> |Supports| SMB[Server Message Block]:::smb

    classDef main fill:#CCFFCC,stroke:#333,stroke-width:2px,color:#000;
    classDef windows fill:#FFD700,stroke:#333,stroke-width:1px,color:#000;
    classDef lustre fill:#FF6347,stroke:#333,stroke-width:1px,color:#000;
    classDef netapp fill:#00BFFF,stroke:#333,stroke-width:1px,color:#000;
    classDef openzfs fill:#32CD32,stroke:#333,stroke-width:1px,color:#000;
    classDef activeDirectory fill:#8A2BE2,stroke:#333,stroke-width:1px,color:#FFF;
    classDef smb fill:#FF69B4,stroke:#333,stroke-width:1px,color:#FFF;
    classDef hpc fill:#FFA500,stroke:#333,stroke-width:1px,color:#000;
    classDef s3 fill:#1E90FF,stroke:#333,stroke-width:1px,color:#000;
    classDef nfs fill:#8FBC8F,stroke:#333,stroke-width:1px,color:#000;
    classDef dataProtection fill:#DA70D6,stroke:#333,stroke-width:1px,color:#000;




```

