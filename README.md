# PRIVACY-PRESERVING GENOMIC ANALYSIS WITH HOMOMORPHIC ENCRYPTION #

## **Abstract** ##

  Genomic analysis has the potential to revolutionize healthcare, but patient data must be protected to maintain privacy. Homomorphic Encryption (HE) enables privacy-preserving analysis by performing computations on encrypted data without revealing the underlying data.
  
## **Scenario** ##

  We consider a hospital that stores patient genomic data on a cloud service (such as Dropbox, Google Drive, or Azure) for research purposes. The hospital is concerned about the privacy and confidentiality of the data, but there is still a risk of data breaches that could result in information leakage. We assume that the cloud service has implemented strong encryption techniques such as AES to protect the data, but there is still a risk of a breach due to vulnerabilities in the cloud service's infrastructure or other factors.
  The hospital wants to explore the use of HE, which allows computation on encrypted data without decrypting it. The hospital can encrypt the genomic data, upload the encrypted data to the cloud, and perform genomic analysis on it using HE. The raw genomic data and analysis results remain encrypted, mitigating the impact of any data breaches. The hospital can download and decrypt only the analysis results, keeping the raw genomic data encrypted in the cloud. This project aims to identify the strengths and limitations of HE for genomic analysis.


| Subject     | Description |
| ----------- | ----------- |
| Protected Assets | Patient genomic data, Personal info |
| Related Parties | Hospital staff, Cloud service provider|
| Security Goals | Ensure the confidentiality & privacy of the patients' data while still allowing for meaningful analysis |
