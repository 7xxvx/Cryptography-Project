# PRIVACY-PRESERVING GENOMIC ANALYSIS WITH HOMOMORPHIC ENCRYPTION #

## **Abstract** ##

  Genomic analysis has the potential to revolutionize healthcare, but patient data must be protected to maintain privacy. Homomorphic Encryption (HE) enables privacy-preserving analysis by performing computations on encrypted data without revealing the underlying data.
  
## **Scenario** ##

  We consider a hospital that stores patient genomic data on a cloud service (such as Dropbox, Google Drive, or Azure) for research purposes. The hospital is concerned about the privacy and confidentiality of the data, but there is still a risk of data breaches that could result in information leakage. We assume that the cloud service has implemented strong encryption techniques such as AES to protect the data, but there is still a risk of a breach due to vulnerabilities in the cloud service's infrastructure or other factors.
  
  The hospital wants to explore the use of HE, which allows computation on encrypted data without decrypting it. The hospital can encrypt the genomic data, upload the encrypted data to the cloud, and perform genomic analysis on it using HE. The raw genomic data and analysis results remain encrypted, mitigating the impact of any data breaches. The hospital can download and decrypt only the analysis results, keeping the raw genomic data encrypted in the cloud. This project aims to identify the strengths and limitations of HE for genomic analysis.

<p align="center">
    <img src="![image](https://user-images.githubusercontent.com/115767103/229334406-edb8d33f-833b-4939-b55b-1fc3be4316be.png)" />
</p>

| Subject     | Description |
| ----------- | ----------- |
| Protected Assets | Patient genomic data, Personal info |
| Related Parties | Hospital staff, Cloud service provider|
| Security Goals | Ensure the confidentiality & privacy of the patients' data while still allowing for meaningful analysis |


## **Solution** ##

  This project explores the use of HE for privacy-preserving genomic analysis. Both FHE & PHE techniques are considered. HE can be used to encrypt the patients' genetic data and perform computations on the encrypted data without revealing any sensitive information. The SEAL HE library and differential privacy techniques can be used to further protect the privacy of the patients' data. By using HE, the hospital can perform genomic analysis on the encrypted data stored in the cloud without risking the exposure of sensitive patient information in the event of a data breach. The SEAL library and differential privacy techniques are used, and the performance and security of FHE and PHE are evaluated.
  
## **Tools** ## 

  The following tools and technologies will be used in this project:
+ The SEAL HE library, which provides a C++ API for implementing various HE schemes, including both FHE and PHE.
+ Differential privacy techniques, which can be used to further protect the privacy of the patients' data by adding random noise to the data before analysis.
+ A cloud storage service, such as Dropbox or Google Drive, for storing and accessing the encrypted patient data.

## **Evaluation** ##

  The performance and security of the HE techniques used in this project will be evaluated using the following approaches:
+ Benchmark datasets and performance metrics will be used to evaluate the performance of the techniques in terms of computation time and memory usage.
+ The security of the techniques will be evaluated by analyzing the attack surface and potential vulnerabilities of the HE schemes used, and by assessing the effectiveness of differential privacy techniques in protecting the privacy of the patients' data.
+ The performance and security of both FHE and PHE techniques will be compared to identify the strengths and limitations of each approach in the context of privacy-preserving genomic analysis.




| Student ID |       Name       |   
| ---------- | ---------------- |
|  21520682  | Lâm Hải Đăng     |
|  21520948  | Nguyễn Đình Kha  |
|  21522292  | Nguyễn Hoàng Lộc |

