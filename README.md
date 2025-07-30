# Vision-Language-Model
Developed a Vision-Language Model combining a contrastive vision encoder with a transformer decoder to generate descriptive text
 conditioned on image inputs.
 • Implemented a SigLIP-based loss function to improve contrastive training scalability, replacing standard CLIP cross-entropy loss for
 large-batch efficiency.
 • Developed custom PyTorch modules for multi-head attention with KV-cache optimization, RMSNorm normalization, and rotary
 positional embeddings to enhance inference performance.
