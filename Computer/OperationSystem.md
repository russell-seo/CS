

# 운영체제

  - 운영체제란?
    
    - 컴퓨터 하드웨어 바로 윗단에 설치되는 소프트웨어를 뜻한다.
    - 컴퓨터 하드웨어와 소프트웨어, 사용자의 사이에서 중재자 역할을 한다.
    - 일반적으로 컴퓨터를 사용하면서 실행한 모든 프로그램들은 운영체제에서 관리하고 제어한다.
    - 대표적인 운영체제로는 Windows, Linux, Mac OSX, IOS 등이 있다.

![image](https://user-images.githubusercontent.com/79154652/143535921-2b0749ca-87aa-4f7b-8b4a-4d8ccefa380f.png)

 
 
# 부팅

  - 컴퓨터의 구조를 단순화하면 아래 그림과 같다.
  
  ![image](https://user-images.githubusercontent.com/79154652/143535994-4158d178-ac5f-4695-a17c-5e797a5a8ca3.png)



  Processor는 일반적으로 CPU를 말한다. Main Memory를 보면 ROM과 RAM으로 나누어져 있다.
  
  - ROM : 비휘발성으로 메모리에서 극히 일부를 차지한다. 전원이 꺼져도 그 안의 내용이 계속 유지된다.
  - RAM : 휘발성으로 메모리의 대부분을 차지하며 실제 프로그램이 할당되는 곳이다. 전원이 꺼지면 메모리안의 모든 내용이 지워진다.

   컴퓨터의 전원이 켜지면 프로세서(CPU)에서 ROM에 있는 내용을 읽는다. ROM 안에는 POST(Power-On Self-Test), 부트 로더(boot loader)가 저장되어 있다.
   POST는 전원이 켜지면 가장 처음에 실행되는 프로그램으로 현재 컴퓨터의 상태를 검사한다. POST는 전원이 켜지면 가장 처음에 실행되는 프로그램으로 현재 컴퓨터의 상태를 검사한다.
   POST작업이 끝나면 부트 로더가 실행된다. 부트 로더는 하드디스크에 저장되어 있는 `운영체제`를 찾아서 메인메모리(RAM)에 가지고온다. 이러한 부트 로더의 과정을 `부팅` 이라고 한다.