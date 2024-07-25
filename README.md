# 📊 Survey Landing Page Repository 🚀

## 🌟 Project Overview
This repository 📁 contains the code and resources for a simple yet impactful landing page. Our goal is to gather valuable feedback from students, businesses, and the community in the South Texas Rio Grande Valley region. 🏫🏢🏡 The survey will inform the development of our Digital Empowerment Interface (DEI) platform, enhancing digital literacy and resource access. 💻🌐

**🔒 Confidentiality and Incentive:**
- All survey contributors will remain anonymous. 🕵️‍♂️
- Personal information is only for the raffle draw, offering a free website design of up to 6 pages or $250.00. 🎨
- Raffle entry requires one completed survey. ✔️
- The survey concludes after reaching the target number of responses. 🎯

**🎁 Raffle Details:**
- A lucky draw 🎰 will select a participant who provided a valid email and a complete survey.
- The winner receives an email notification 📧 and must accept the offer within 14 calendar days.
- The free website design offer expires after 14 days from the email date. ⏳
- Participation is free! This is our thank-you 🙏 to the community for their valuable feedback, raffle will be held at the end of the survey.

## 📈 Statistical Approach for Sample Size
# - Target sample size for each group follows statistical guidelines:
# np(1-p) ≥ 10
# n < .05N or n ≥ 30
# α = .01 , 99% conficence interval
# E = 1%


- **n:** Sample size
- **N:** Population size
- **p:** Population proportion
- **$$\bar{x}$$** Sample mean
- **$$\hat{p}$$** Sample proportion

Given quantitative variables and uncertain population distribution, we ensure \( n ≥ 30 \).

Construct a 99% confidence interval with 1% error for DEI viability:
# - To determine the required sample size needed Ill use:
# $$\hat{p}(1 - \hat{p})\left(\frac{z_{\alpha/2}}{E}\right)^2$$
# $$\hat{p}(1 - \hat{p})$$ = .50 (due to not having any prior data)

# $$\left(\frac{z_{\alpha/2}}{E}\right)^2$$ = $$\left(\frac{z_{.005}}{.01}\right)^2$$


# In this case we are dealing with quantitative variables and will ensure n >= 30 since the possibility of verifying the population to be normally distributed is unlikley to be possible. 

# I will construct a 99% confidence interval to determine where the results from the survey resolve in order to determine (DEI) viability. 
# Well use the normal probability density function expression:
# $$\int \frac{1}{\sigma\sqrt{2\pi}} e^{-\frac{1}{2}\left(\frac{x - \mu}{\sigma}\right)^2} \,dx $$
# I will take that over a 99% interval:
#  ![Complex Integral Formula](https://latex.codecogs.com/gif.latex?%5Cint_%7Bx_1%7D%5E%7Bx_2%7D%20%5Cfrac%7B1%7D%7B%5Csigma%5Csqrt%7B2%5Cpi%7D%7D%20e%5E%7B-%5Cfrac%7B1%7D%7B2%7D%5Cleft%28%5Cfrac%7Bx%20-%20%5Cmu%7D%7B%5Csigma%7D%5Cright%29%5E2%7D%20%2C%20dx%20-%20%5Cint_%7B-%5Cinfty%7D%5E%7Bx_1%7D%20%5Cfrac%7B1%7D%7B%5Csigma%5Csqrt%7B2%5Cpi%7D%7D%20e%5E%7B-%5Cfrac%7B1%7D%7B2%7D%5Cleft%28%5Cfrac%7Bx%20-%20%5Cmu%7D%7B%5Csigma%7D%5Cright%29%5E2%7D%20%2C%20dx)
# - The resulting calculation can be confirmed against the Statistician's z-table value for α/2 = .005 => z = 2.58 📊

# $$\left(\frac{2.58}{.01}\right)^2$$ = 66564
# and finally, we assume $$\hat{p}$$ = 0.5 since we have no prior data:
# n = .5(66564)
# n = 33282

## Next apply (FPC) Finite Population Correction, 
# ![Formula](https://latex.codecogs.com/gif.latex?n_%7B%5Ctext%7Bcorrected%7D%7D%20%3D%20%5Cfrac%7Bn_%7B%5Ctext%7Binitial%7D%7D%7D%7B1%20&plus;%20%5Cfrac%7Bn_%7B%5Ctext%7Binitial%7D%7D%20-%201%7D%7BN%7D%7D)
# - Since N is know from the U.S Census Bureau data.
# N = 1,404,225
# z = 2.576  
# p = 0.5 
# E = 0.01 
# $$n_{\text{initial}}$$ = 33282
# ![Formula](https://latex.codecogs.com/gif.latex?n_%7B%5Ctext%7Bcorrected%7D%7D%20%3D%20%5Cfrac%7B33282%7D%7B1%20&plus;%20%5Cfrac%7B33282%20-%201%7D%7B1%2C404%2C225%7D%7D)
**Required Sample Size:**
# - 32,511 surveys is our target. 🎯

## Lastly Ill use stratification to applied equaly, on the basis of the overlapping nature of respondents among groups

# Allocate approximately 32,511/3​ surveys to each group:
# Required distribution = 
# Students: 32,511 / 3 ≈ 10,837 surveys
# Business Owners: 32,511 / 3 ≈ 10,837 surveys
# Community Members: 32,511 / 3 ≈ 10,837 surveys

## 🌈 Features
- **🖥 Landing Page**: Engaging webpage introducing the survey and encouraging participation.
- **📱 QR Code Integration**: Scan to access the survey directly.
- **📐 Responsive Design**: Great usability across devices.
- **📞 Contact Information**: Reach out to us for info or support.

## 🚀 Getting Started
Follow these steps to get the project up and running on your local machine for development and testing.

## 🤝 Contributing
Join our vibrant community on Discord [here](https://discord.gg/Q6HxGRzg) for our code of conduct and contribution guidelines.

## ✍️ Authors
- **GuyMorganB** - *Initial Work* - [GitHub Profile](https://github.com/guymorganb)

## 📜 License
Licensed under the MIT License - see the [LICENSE.md](LICENSE_FILE_LINK) file for details.

## 🙌 Acknowledgments
- A big thanks to all contributors and supporters.
- Inspired by community feedback and
- Hat tip to anyone whose code was used
- Inspiration
- etc.
