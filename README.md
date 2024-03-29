# enable-it
e-Nable Italia Bionic Platform

This project aims to create a general purpose hardware platform that can be used to develop bionic/electronics controlled devices

## Boards
### Controllers - controller boards with a general purpose CPU, exposing a standard bus interface (see B2BCB specifications)
* ESP32 Wroom board Rev. B - ESP32 S3 based 

### Debug - debug, testing boards
* Debug Board Rev. A, mating board useful for debug and testing purposes

## Project directory layout
- docs, contains general documents
- schematics,  contains schematics in PDF format
- build, contains CAM Output files for board production
- EAGLE, contains project EAGLE files

## Project updates
220913 - repo init, added project doc & rev. 0.9 of ESP32 controller board

220922 - added debug board, added Rev. B of control board

220927 - updated debug board to Rev. A (added bottom connectors to allow tests of stacked boards)

230305 - added EMG Module - Rev B, changed name to enable-it

## KNOWN ISSUES

- ESP32 Controller board flash programming problem, rework required to fix this issue 
- Power connectors are not correctly aligned in all the boards, rework required to fix this issue
- Wrong height of 40pin connectors (4mm instead of 3mm)
- EMG Module power issue: short circuitt between AVDD & AVSS (PS$32 AVSS connected to V+ instead of V-)

## LIMITATION OF LIABILITY.
UNDER NO CIRCUMSTANCES AND UNDER NO LEGAL THEORY, WHETHER TORT (INCLUDING NEGLIGENCE), CONTRACT, OR OTHERWISE, SHALL YOU, THE INITIAL DEVELOPER, ANY OTHER CONTRIBUTOR, OR ANY DISTRIBUTOR OF COVERED CODE, OR ANY SUPPLIER OF ANY OF SUCH PARTIES, BE LIABLE TO ANY PERSON FOR ANY INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES OF ANY CHARACTER INCLUDING, WITHOUT LIMITATION, DAMAGES FOR LOSS OF GOODWILL, WORK STOPPAGE, COMPUTER FAILURE OR MALFUNCTION, OR ANY AND ALL OTHER COMMERCIAL DAMAGES OR LOSSES, EVEN IF SUCH PARTY SHALL HAVE BEEN INFORMED OF THE POSSIBILITY OF SUCH DAMAGES. THIS LIMITATION OF LIABILITY SHALL NOT APPLY TO LIABILITY FOR DEATH OR PERSONAL INJURY RESULTING FROM SUCH PARTY'S NEGLIGENCE TO THE EXTENT APPLICABLE LAW PROHIBITS SUCH LIMITATION. SOME JURISDICTIONS DO NOT ALLOW THE EXCLUSION OR LIMITATION OF INCIDENTAL OR CONSEQUENTIAL DAMAGES, SO THIS EXCLUSION AND LIMITATION MAY NOT APPLY TO YOU.
