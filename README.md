# GEMMurai 🥋⚔️🙇

*The Way of the Matrix Warrior*

A training dojo for mastering high-performance linear algebra from first principles. This is not a production library—it's a forge for understanding how the masters like Kazushige Goto achieved computational enlightenment.

## The Path

Transform abstract linear algebra theory into blazing fast kernels. From Axler's vector spaces to hand-tuned assembly that rivals commercial BLAS implementations. (ambition is $\frac{7}{10}$ths of the way).

### The Three Sacred Levels

**BLAS Level 1** - *The Foundation* 
- Vector-vector operations: `O(n)` work on `O(n)` data
- Operations: dot products (`dot`), vector scaling (`scal`), addition (`axpy`)
- *Sensei says: "Master the simple before attempting the complex"*

**BLAS Level 2** - *The Ascension*
- Matrix-vector operations: `O(n²)` work on `O(n²)` data  
- Operations: matrix-vector multiply (`gemv`), rank-1 updates (`ger`)
- *Where cache awareness begins to matter*

**BLAS Level 3** - *The Mastery*
- Matrix-matrix operations: `O(n³)` work on `O(n²)` data
- The holy grail: `GEMM` (General Matrix Multiply)
- *Optimal arithmetic intensity, where legends are forged*

## Training Philosophy

- **Rigor First**: Understand the mathematics (Axler → Trefethen & Bau)
- **Measure Everything**: Profile-driven optimization, not premature cleverness
- **Incremental Mastery**: Generic C → Cache blocking → SIMD → Assembly
- **No Shortcuts**: Build intuition through implementation

## Current Kata

- [ ] Basic BLAS-1 implementations
- [ ] Cache-conscious GEMV
- [ ] The legendary GEMM kernel
- [ ] Assembly optimization passes
- [ ] Benchmark against OpenBLAS/MKL

*δῶς μοι πᾶ στῶ καὶ τὰν γᾶν κινάσω*

*道は長い*
