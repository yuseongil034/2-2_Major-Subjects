# 📚 전자공학과 2학년 전공과목 학습 정리

## 📋 과목 개요
- [전자기학 (Electromagnetics)](#1-전자기학-electromagnetics)
- [회로이론 (Circuit Theory)](#2-회로이론-circuit-theory)
- [공업수학 (Engineering Mathematics)](#3-공업수학-engineering-mathematics)
- [C++ 프로그래밍](#4-c-프로그래밍)
- [미적분학 복습 (Calculus)](#5-미적분학-복습-Calculus)
- [정보통신개론 (Introduction to Information & Communication)](#6-정보통신개론-introduction-to-information--communication)

---

## 1. 전자기학 (Electromagnetics)

### 📖 이론 정리
- [전기력과 전계, 자석과 전자스핀, 전류와 자계](전기력_전계_자석_전자스핀_전류_자계.md)
- [전계와 자계의 독립성, 매질변수, 전자기파](전계,자계_독립성_매질변수_전자기파.md)
- [차원과 단위, 스칼라와 벡터](차원과_단위.md)
- [직교좌표계와 벡터의 적분](백터좌표계.md)
- [스칼라 및 벡터의 미분](스칼라_백터_미분.md)
- [벡터의 발산과 회전](스칼라_백터_미분.md)
- [Coulomb의 법칙과 전계](쿨롱의법칙.md)
- [전위, 전속밀도와 Gauss 법칙](가우스법칙_도전전류와저항.md)
- [도전전류와 저항, 경계치 문제](가우스법칙_도전전류와저항.md)
- [정전에너지](정전에너지.md)

---

## 2. 회로이론 (Circuit Theory)
### 📖 이론 정리
- [기본 회로소자와 전기회로](기본소자정리.md)
- [전압법칙과 전류법칙](KCL&KVL.md)
- [기본적인 마디해석법 및 메쉬해석법](NODAL&MESH.md)
- [편리한 회로 해석 기법](편리한_회로해석_기법.md)
- [연산증폭기](circuit_theory/operational_amplifiers.md)
- [커패시터와 인덕터](circuit_theory/capacitors_inductors.md)
- [기본적인 RL과 RC 회로](circuit_theory/rl_rc_circuits.md)
- [RLC 회로](circuit_theory/rlc_circuits.md)
- [정현파의 정상상태 해석](circuit_theory/sinusoidal_steady_state.md)
- [교류 회로 전력 해석](circuit_theory/ac_power_analysis.md)
- [다상 회로](circuit_theory/polyphase_circuits.md)
- [자기 결합 회로](circuit_theory/magnetically_coupled_circuits.md)
- [s-영역에서의 회로 해석](circuit_theory/s_domain_analysis.md)
- [주파수 응답](circuit_theory/frequency_response.md)
- [2포트 회로망](circuit_theory/two_port_networks.md)
- [푸리에 회로 해석](circuit_theory/fourier_circuit_analysis.md)

### 🧮 문제풀이
- [DC 회로 문제](circuit_theory/problems/dc_circuits.md)
- [AC 회로 문제](circuit_theory/problems/ac_circuits.md)
- [과제 풀이](circuit_theory/problems/assignments.md)



---

## 3. 공업수학 (Engineering Mathematics)

### 📖 이론 정리

#### 🔢 미분방정식 (Differential Equations)
- [1차 미분방정식](engineering_math/differential_equations/first_order.md)
- [2차 미분방정식](engineering_math/differential_equations/second_order.md)
- [고차 미분방정식](engineering_math/differential_equations/higher_order.md)
- [연립 미분방정식](engineering_math/differential_equations/systems.md)

#### 📊 라플라스 변환 (Laplace Transform)
- [라플라스 변환 기초](engineering_math/laplace/basics.md)
- [역 라플라스 변환](engineering_math/laplace/inverse.md)
- [미분방정식 해법](engineering_math/laplace/solving_de.md)

#### 🌊 푸리에 급수와 변환 (Fourier Series & Transform)
- [푸리에 급수](engineering_math/fourier/series.md)
- [푸리에 변환](engineering_math/fourier/transform.md)
- [이산 푸리에 변환](engineering_math/fourier/dft.md)

#### 📈 복소함수 (Complex Functions)
- [복소수와 복소평면](engineering_math/complex/complex_numbers.md)
- [복소함수의 미분](engineering_math/complex/differentiation.md)
- [복소적분](engineering_math/complex/integration.md)
- [유수정리](engineering_math/complex/residue_theorem.md)

#### 🔢 선형대수 (Linear Algebra)
- [행렬과 행렬식](engineering_math/linear_algebra/matrices.md)
- [고유값과 고유벡터](engineering_math/linear_algebra/eigenvalues.md)
- [벡터공간](engineering_math/linear_algebra/vector_spaces.md)

### 🧮 문제풀이
- [미분방정식 문제](engineering_math/problems/differential_eq.md)
- [라플라스 변환 문제](engineering_math/problems/laplace.md)
- [푸리에 해석 문제](engineering_math/problems/fourier.md)
- [복소해석 문제](engineering_math/problems/complex.md)



---

## 4. C++ 프로그래밍

### 📖 기본 문법
- [C++ 기초 문법](cpp/basics/syntax_basics.md)
- [변수와 자료형](cpp/basics/variables_datatypes.md)
- [연산자](cpp/basics/operators.md)
- [제어구조 (if, for, while)](cpp/basics/control_structures.md)
- [함수](cpp/basics/functions.md)
- [배열과 포인터](cpp/basics/arrays_pointers.md)

### 🏗️ 객체지향 프로그래밍
- [클래스와 객체](cpp/oop/classes_objects.md)
- [생성자와 소멸자](cpp/oop/constructors_destructors.md)
- [상속](cpp/oop/inheritance.md)
- [다형성](cpp/oop/polymorphism.md)
- [연산자 오버로딩](cpp/oop/operator_overloading.md)
- [템플릿](cpp/oop/templates.md)

### 📚 STL (Standard Template Library)
- [벡터 (Vector)](cpp/stl/vector.md)
- [리스트 (List)](cpp/stl/list.md)
- [스택과 큐](cpp/stl/stack_queue.md)
- [맵과 셋](cpp/stl/map_set.md)
- [알고리즘](cpp/stl/algorithms.md)

### 💾 파일 입출력
- [파일 읽기/쓰기](cpp/file_io/file_operations.md)
- [바이너리 파일 처리](cpp/file_io/binary_files.md)

### 🔧 실습 프로젝트
- [계산기 프로그램](cpp/projects/calculator/)
- [학생 성적 관리 시스템](cpp/projects/grade_management/)
- [간단한 게임](cpp/projects/simple_game/)
- [자료구조 구현](cpp/projects/data_structures/)

### 🧮 문제풀이
- [기초 문제](cpp/problems/basic_problems.md)
- [알고리즘 문제](cpp/problems/algorithm_problems.md)
- [과제 풀이](cpp/problems/assignments.md)

---

## 5. 미적분학 복습 (Calculus)

- [함수와 극한](미적분학_1_함수의_극한.md)
- [도함수와 미분법의 응용](미적분학_2_미분의응용.md)
- [적분과 적분법의 응용](미적분학_3_적분의응용.md)
- [역함수: 지수함수, 로그함수, 역삼각함수](미적분학_4_역함수.md)
- [적분 방법: 치환적분, 부분적분, 삼각치환 등](미적분학_5_치환적분.md)
- [적분법의 다양한 응용: 면적, 부피, 물리적 해석](미적분학_6_적분응용.md)
- [매개변수방정식과 극좌표](미적분학_7_매개변수.md)
- [무한수열과 무한급수](미적분학_8_무한급수.md)
- [다중적분: 이중적분, 삼중적분](미적분학_9_다중적분.md)
- [복소수와 오일러 공식](미적분학_10_복소수.md)
- [삼각함수의 정의와 미분 적분](미적분학_11_삼각함수.md)
- [지수함수와 로그함수의 미분과 적분](미적분학_12_지수로그미분.md)


---

## 6. 정보통신개론 (Introduction to Information & Communication)

### 📖 이론 정리

- [OT](info_comm/basics/communication_systems.md) 
- [2주차](info_comm/basics/signals_spectrum.md) 
- [3주차](info_comm/basics/analog_digital.md) 
- [4주차](info_comm/basics/noise_interference.md)
- [5주차](info_comm/information_theory/entropy.md) 
- [6주차](info_comm/information_theory/channel_capacity.md) 
- [7주차](info_comm/information_theory/source_coding.md) 
- [중간고사](info_comm/information_theory/channel_coding.md)
- [9주차](info_comm/modulation/amplitude_modulation.md) 
- [10주차](info_comm/modulation/frequency_modulation.md)
- [11주차](info_comm/modulation/phase_modulation.md)
- [12주차](info_comm/modulation/digital_modulation.md)
- [13주차](info_comm/networking/osi_model.md)
- [14주차](info_comm/networking/tcp_ip.md)
- [기말고사](info_comm/wireless/channel_characteristics.md)



---


