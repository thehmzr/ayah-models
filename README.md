# Ayah model files

Files the **Ayah** app (offline Quran recitation companion) downloads once, on first use.
They're hosted here because the app's own code repository is private.

Files are attached to [Releases](../../releases), never committed to git.

## Release `phoneme-v3.1`: Quran-Lab zipformer_p-arabic-v3.1

An unmodified copy of files from [Quran-Lab/zipformer_p-arabic-v3](https://huggingface.co/Quran-Lab/zipformer_p-arabic-v3)
(commit `3da514fc833b22c902ee466a7710cf399896f2f0`): a streaming phoneme recogniser for Quran recitation (Hafs ʿan ʿĀṣim).

| File | Size (bytes) | SHA-256 |
|---|---|---|
| `zipformer_p_arabic_v3.1.int8.onnx` | 72705392 | `31755836528da336a6192121cd7bc82cb41752dddb65566fd000b89c8686da6b` |
| `tokens.txt` | 2346 | `252c10687e442aa9291973065fae19fa39bcd681c4f5612ec496a647e20b43a1` |
| `ordered_quran_phonemes.json` | 5106711 | `4782e90e190a59207f5d74a909dd917a0cfead1959338d1fbc97fe55faf1c09c` |
| `LICENSE` | 7041 | `77526bdbfac94132e5114c3a34492c33f915e4b7f310f00b9995500d3610cab5` |

### Licence: Quran-Lab No-Profit License 1.2

These files are under the [Quran-Lab NPL-1.2](LICENSE), not under any other licence. In short:

- **Never charged for.** Not the model, not access to it, not any feature it powers. No paywall, no subscription, no ads.
- Its output is **not an authoritative religious ruling** on anyone's recitation.
- Any app built on it must state clearly that **automatic tajweed feedback can be wrong and does not replace a qualified teacher.**
- Derivatives must stay under the same licence (share-alike), and the LICENSE file must travel with the files.

Read the full [LICENSE](LICENSE). All credit for the model goes to Quran-Lab.
