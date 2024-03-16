# tsdGAN: A generative adversarial network approach for removing electrocardiographic interference from electromyographic signals 
## Authors
**Lucas Haberkamp** 
- Naval Medical Research Unit - Dayton, Wright-Patterson Air Force Base, OH, USA 
- Leidos, Reston, VA, USA 
  
**Charles A. Weisenbach** 
- Naval Medical Research Unit - Dayton, Wright-Patterson Air Force Base, OH, USA

**Peter Le**  
- Air Force Research Laboratory, 711th Human Performance Wing, Wright-Patterson Air Force Base, OH, USA

## Abstract
This paper introduces tsdGAN, a novel deep learning approach specifically designed to remove electrocardiographic (ECG) interference from electromyographic (EMG) signals. Unlike conventional supervised deep learning techniques, tsdGAN does not require pre-existing uncorrupted EMG signals for training, addressing a common obstacle in developing deep learning solutions for biomedical signal denoising. By employing adversarial training strategies, tsdGAN learns solely from prior knowledge of EMG segment locations with significant ECG interference. We trained tsdGAN using a synthetic dataset that emulated an experimental dataset lacking an uncorrupted baseline EMG signal. Then, we validated the efficacy of tsdGAN using a synthetic dataset with known uncorrupted EMG signals. We compared tsdGAN's performance against established methods, including template subtraction, Butterworth high-pass filtering, and dynamic filtration, across both time and frequency domains. The results demonstrate that tsdGAN substantially improves the signal-to-noise ratio and achieves a closer approximation to the actual power spectral density, indicating a significant enhancement in the quality of the denoised EMG signals. Overall, tsdGAN holds promise for denoising real-world EMG datasets corrupted with ECG interference and can potentially lead to more dependable biomechanical interpretations in future studies.

## Contact
For any further inquiries or discussions related to this work, please reach out to the primary correspondent: lucas.haberkamp.ctr@us.af.mil

## Acknowledgements
DISTRIBUTION STATEMENT A. Approved for public release. Distribution is unlimited. The views expressed in this article reflect the results of research conducted by the authors and do not necessarily reflect the official policy or position of the Department of the Navy, Department of the Air Force, Department of Defense, nor the United States Government.    
Charles Weisenbach and Peter Le are employees of the U.S. Government. This work was prepared as part of their official duties. Title 17 U.S.C. 105 provides that copyright protection under this title is not available for any work of the U.S. Government. Title 17 U.S.C. 101 defines a U.S. Government work as work prepared by a military service member or employee of the U.S. Government as part of that person's official duties.  
The authors are thankful for the technical assistance provided by Alannah Gernon, who played a crucial role in data collection, and Nicholas Robinson, for his valuable contributions in reviewing the manuscript.

## Funding
This work was funded by the Defense Health Agency, Joint Program Committee-5 (JPC-5), work unit number (H2101).  
