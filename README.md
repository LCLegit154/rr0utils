# rr0utils

A collection of lightweight utility binaries written in pure C for fun, low-level manipulation, and testing.

## Utilities

- **mkfill**: A fast utility designed to generate files filled with specific byte patterns or data streams.
- **fcorrupt**: A tool for introducing controlled corruption into files for resilience testing, fuzzing, and error-handling verification.

## Building

Clone the repository and compile using any standard C compiler (such as `gcc` or `clang`):

\`\`\`bash
git clone https://github.com/yourusername/rr0utils.git
cd rr0utils
gcc -O3 mkfill.c -o mkfill
gcc -O3 fcorrupt.c -o fcorrupt
\`\`\`

## Usage

### mkfill
\`\`\`bash
./mkfill [options] <output_file>
\`\`\`

### fcorrupt
\`\`\`bash
./fcorrupt <target_file> [corruption_offset]
\`\`\`

## License
This project is open-source and available under the GNU General Public License v3.0 License.
