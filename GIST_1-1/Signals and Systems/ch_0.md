# Signals and Systems

 이 포스팅은 랜덤 프로세스 공부를 위해 신호 및 시스템을 공부한 내용을 정리한 글입니다. 엄밀하지 않거나 누락된 내용이 있을 수 있습니다. 

##  Ch 0. Introduction



**Signal**: ==물리량==을 ==수학적==으로 모델링한 것. 

어떤 수학적 객체를 썼느냐에 따라 그 형태는 스칼라, 벡터, 행렬, 텐서뿐만 아니라 sequence, 다항식, field, waveform 등 다양하게 나타난다. 여기서 sequence의 경우가 DT Signal, waveform이 CT Signal에 해당하게 된다. 

- **DT(Discrete-TIme) Signal**: 이산 시간 $$t (t\in \Z )$$에 의해 그 값 $$x(x \in \R^n)$$이 정해지는 Sequence
- **CT(Continuous-Time) Signal**: 연속 시간 $$t(t \in \R)$$에 의해 그 값 $$x(x\in \R^n)$$이 정해지는 Waveform



- 주의) **Digital Signal**: Resolution이 제한되어 있는 DT Signal. 더 깊은 개념이며, DT Signal과 엄밀히 다름. 

**System**: input을 output으로 mapping하는 mapping rule

- 



