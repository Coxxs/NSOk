# NSOk

NSOk is a hex string generator with a very particular set of skills. It requires a rooted Android phone.

## Usage

1. Install [Magisk](https://github.com/topjohnwu/Magisk/releases)
    - Disable "Enforce DenyList" in Magisk Settings
    - Tick NSO App in DenyList

2. Install [LSPosed](https://github.com/LSPosed/LSPosed/releases/tag/v1.8.6) and [Shamiko](https://github.com/LSPosed/LSPosed.github.io/releases) in Magisk

3. Install NSOk, enable it in LSPosed

4. Reboot, then open NSO App (2.5.1)

5. NSOk is now running on the `9000` port of your phone. Forward it to your PC using adb (`adb tcp:9000 tcp:9000`), then you can access it using `http://127.0.0.1:9000/f`

Special thanks to [f-API](https://github.com/imink-app/f-API).

If you are interested in how it works: [jadx](https://github.com/skylot/jadx).

## Disclaimer

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
