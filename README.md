# multiplayer-2d-soccer-game-analog

## Project Description
- 본 프로젝트는 FPGA보드와 컴퓨터, VGA디스플레이를 활용하여 비디오 게임을 할수 있는 하드웨어적 환경을 조성하고, System Verilog(HDL)을 이용하여 데이터 파이프라인을 설계하여 여러 모듈이 상호 호환 되도록 하고, NIOS를 이용하여 제작한 C++비디오게임이 FPGA칩에서 적절한 메모리를 사용하여 게임을 할 수 있도록 합니다.
- 이 프로젝트의 경우 모든 게임은 C++를 이용하여 설계가 되지만, 모든 기기가 FPGA보드와 연결이 되므로 FPGA에 적합한 데이터 파이프라인도 동시에 설계해야 합니다.
최대 2인의 사용자가 이용 가능한 이 게임은, C++를 이용하여 동작, 게임의 룰, 진행 방식 등 모든 게임의 요소를 설계하게 되며, 그 외에 C++를 이용한 NIOS II 프로그램이 FPGA와 연결될 수 있도록 NIOS II와 FPGA 사이의 데이터 파이프 라인을 설계하는데 이를 통하여 VGA 디스플레이에 게임 영상이 나올 수 있도록 하며, 공 , 플레이어, 필드, 및 제약 조건 등을 설정 하는 것은 System Verilog를 이용합니다. 

## Reference 
- [fpga-games-2d-soccer-multiplayer.docx.docx](https://github.com/FlexEasy/multiplayer-2d-soccer-game-analog/files/7720627/fpga-games-2d-soccer-multiplayer.docx.docx)
