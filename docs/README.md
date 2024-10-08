## AdvDualTTS: Dual Style Embeddings with Adversarial Learning in Non-parallel Style Transfer

The content leakage problem in style-transfer text-to-speech (TTS) systems often arises when the semantic contents of reference speech excessively influence the synthesis result, degrading its perceptual quality. To mitigate this problem, we introduce AdvDualTTS, a high-quality TTS system with dual-style embeddings and an adversarial learning strategy. Our TTS model explicitly separates style embeddings into text-dependent and text-independent representations. The former captures the inherent stress patterns of input text using a BERT-based style predictor, while the latter captures the context-free prosody attributes of the reference speech. Additionally, we adopt an adversarial learning strategy to help the model learn how to express various styles in the non-parallel style transfer setting. The subjective and objective experimental results verify the superiority of our TTS system over conventional methods. (MOS: 4.36, ABX Preference Test: 68.26%)

### Generated Speech Samples in Main Result

| Reference Speech                                             | VITS-GST                             | AdvDualTTS                                                 |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| <audio src="./samples/1/reference.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/1/vits_gst.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/1/advdualtts.wav" type="audio/wav" controls="" preload=""></audio> |
| <audio src="./samples/2/reference.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/2/vits_gst.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/2/advdualtts.wav" type="audio/wav" controls="" preload=""></audio> |
| <audio src="./samples/3/reference.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/3/vits_gst.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/3/advdualtts.wav" type="audio/wav" controls="" preload=""></audio> |
| <audio src="./samples/4/reference.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/4/vits_gst.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/4/advdualtts.wav" type="audio/wav" controls="" preload=""></audio> |
| <audio src="./samples/5/reference.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/5/vits_gst.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/5/advdualtts.wav" type="audio/wav" controls="" preload=""></audio> |
| <audio src="./samples/6/reference.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/6/vits_gst.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/6/advdualtts.wav" type="audio/wav" controls="" preload=""></audio> |
| <audio src="./samples/7/reference.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/7/vits_gst.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/7/advdualtts.wav" type="audio/wav" controls="" preload=""></audio> |
| <audio src="./samples/8/reference.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/8/vits_gst.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/8/advdualtts.wav" type="audio/wav" controls="" preload=""></audio> |
| <audio src="./samples/9/reference.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/9/vits_gst.wav" type="audio/wav" controls="" preload=""></audio> | <audio src="./samples/9/advdualtts.wav" type="audio/wav" controls="" preload=""></audio> |



### Average Speech Sample

| Original Speech                    |  Average Speech                    |   
|-------------------------------------|-------------------------------------|
| <img src="samples/average/original_mel.png" alt="Original Mel-spectrogram" width="500"/> | <img src="samples/average/average_mel.png" alt="Average Mel-spectrogram" width="500"/> |
| <audio src="./samples/average/original.mp3" type="audio/mp3" controls="" preload=""></audio> | <audio src="./samples/average/average.wav" type="audio/wav" controls="" preload=""></audio> | 
