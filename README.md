# 📚 전자공학과 2학년 전공과목 학습 정리

## 📋 과목 개요
- [전자기학 (Electromagnetics)](#1-전자기학-electromagnetics)
- [회로이론 (Circuit Theory)](#2-회로이론-circuit-theory)
- [공업수학 (Engineering Mathematics)](#3-공업수학-engineering-mathematics)
- [C++ 프로그래밍](#4-c-프로그래밍)
- [확률 및 랜덤변수 (Probability & Random Variables)](#5-확률-및-랜덤변수-probability--random-variables)
- [정보통신개론 (Introduction to Information & Communication)](#6-정보통신개론-introduction-to-information--communication)

---

## 1. 전자기학 (Electromagnetics)

### 📖 이론 정리
- [벡터 해석](백터의_개념.md)
- [쿨롱의 법칙과 전기장](electromagnetics/coulomb_law.md)
- [가우스 법칙](electromagnetics/gauss_law.md)
- [전위와 전기에너지](electromagnetics/electric_potential.md)
- [유전체와 경계조건](electromagnetics/dielectrics.md)
- [정전용량과 축전기](electromagnetics/capacitance.md)
- [전류와 저항](electromagnetics/current_resistance.md)
- [자기장과 자기력](electromagnetics/magnetic_field.md)
- [패러데이 법칙](electromagnetics/faraday_law.md)
- [맥스웰 방정식](electromagnetics/maxwell_equations.md)

### 🧮 문제풀이
- [기본 문제](electromagnetics/problems/basic_problems.md)
- [중간고사 대비](electromagnetics/problems/midterm_prep.md)
- [기말고사 대비](electromagnetics/problems/final_prep.md)


---

## 2. 회로이론 (Circuit Theory)
### 📖 이론 정리
- [기본 회로소자와 전기회로](기본소자정리.md)
- [전압법칙과 전류법칙](circuit_theory/voltage_current_laws.md)
- [기본적인 마디해석법 및 메쉬해석법](circuit_theory/nodal_mesh_analysis.md)
- [편리한 회로 해석 기법](circuit_theory/convenient_analysis_methods.md)
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

## 5. 확률 및 랜덤변수 (Probability & Random Variables)

### 📖 이론 정리

#### 🎲 확률 기초 (Probability Basics)
- [확률의 정의와 공리](probability/basics/probability_axioms.md)
- [조건부 확률](probability/basics/conditional_probability.md)
- [베이즈 정리](probability/basics/bayes_theorem.md)
- [독립성](probability/basics/independence.md)

#### 📊 랜덤변수 (Random Variables)
- [이산 랜덤변수](probability/random_variables/discrete_rv.md)
- [연속 랜덤변수](probability/random_variables/continuous_rv.md)
- [확률질량함수와 확률밀도함수](probability/random_variables/pmf_pdf.md)
- [누적분포함수](probability/random_variables/cdf.md)
- [기댓값과 분산](probability/random_variables/expectation_variance.md)

#### 📈 확률분포 (Probability Distributions)
- [이항분포](probability/distributions/binomial.md)
- [포아송분포](probability/distributions/poisson.md)
- [정규분포](probability/distributions/normal.md)
- [지수분포](probability/distributions/exponential.md)
- [균등분포](probability/distributions/uniform.md)

#### 🔗 다중 랜덤변수 (Multiple Random Variables)
- [결합확률분포](probability/multiple_rv/joint_distribution.md)
- [주변확률분포](probability/multiple_rv/marginal_distribution.md)
- [공분산과 상관계수](probability/multiple_rv/covariance_correlation.md)
- [조건부 기댓값](probability/multiple_rv/conditional_expectation.md)

#### 📏 극한정리 (Limit Theorems)
- [대수의 법칙](probability/limit_theorems/law_of_large_numbers.md)
- [중심극한정리](probability/limit_theorems/central_limit_theorem.md)

### 🧮 문제풀이
- [기초 확률 문제](probability/problems/basic_probability.md)
- [랜덤변수 문제](probability/problems/random_variables.md)
- [확률분포 문제](probability/problems/distributions.md)
- [응용 문제](probability/problems/applications.md)



---

## 6. 정보통신개론 (Introduction to Information & Communication)

### 📖 이론 정리

#### 📡 통신 시스템 기초
- [통신 시스템 개요](info_comm/basics/communication_systems.md)
- [신호와 스펙트럼](info_comm/basics/signals_spectrum.md)
- [아날로그와 디지털 통신](info_comm/basics/analog_digital.md)
- [잡음과 간섭](info_comm/basics/noise_interference.md)

#### 📊 정보 이론 (Information Theory)
- [정보량과 엔트로피](info_comm/information_theory/entropy.md)
- [채널 용량](info_comm/information_theory/channel_capacity.md)
- [소스 코딩](info_comm/information_theory/source_coding.md)
- [채널 코딩](info_comm/information_theory/channel_coding.md)

#### 🔄 변조와 복조 (Modulation & Demodulation)
- [진폭 변조 (AM)](info_comm/modulation/amplitude_modulation.md)
- [주파수 변조 (FM)](info_comm/modulation/frequency_modulation.md)
- [위상 변조 (PM)](info_comm/modulation/phase_modulation.md)
- [디지털 변조](info_comm/modulation/digital_modulation.md)

#### 🌐 네트워크 기초
- [OSI 7계층](info_comm/networking/osi_model.md)
- [TCP/IP 프로토콜](info_comm/networking/tcp_ip.md)
- [데이터 링크 계층](info_comm/networking/data_link.md)
- [네트워크 계층](info_comm/networking/network_layer.md)

#### 📶 무선 통신
- [무선 채널 특성](info_comm/wireless/channel_characteristics.md)
- [안테나 기초](info_comm/wireless/antenna_basics.md)
- [다중 접속 기법](info_comm/wireless/multiple_access.md)
- [셀룰러 시스템](info_comm/wireless/cellular_systems.md)

### 🧮 문제풀이
- [통신 시스템 문제](info_comm/problems/communication_systems.md)
- [정보 이론 문제](info_comm/problems/information_theory.md)
- [변조 기법 문제](info_comm/problems/modulation.md)
- [네트워킹 문제](info_comm/problems/networking.md)


---


