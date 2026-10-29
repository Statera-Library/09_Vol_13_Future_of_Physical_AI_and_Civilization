**Volume 13. Future of Physical AI and Civilization**

# Chapter 07. Open Research Questions

## 07.01. What Remains Unsolved in Physical AI

![](images/image1.png){width="7.268055555555556in" height="7.268055555555556in"}

피지컬 인공지능(Physical AI)은 좁은 범위의 사전 프로그래밍된 기계에서 인식(Perception), 추론(Reasoning), 학습(Learning), 자율 행동(Autonomous Action)이 가능한 시스템으로 발전해 왔다. 그러나 특정 작업에 특화된 로봇의 능력에서 범용 물리 지능(General Physical Intelligence)으로 전환하는 과정은 아직 완성되지 않았다. 로봇은 통제된 환경에서 뛰어난 작업 수행 능력을 보여주지만, 익숙하지 않은 물체와 환경, 다양한 상황에서 안정적으로 작동하는 것은 여전히 근본적인 과학적 과제로 남아 있다.

가장 중요한 미해결 문제 중 하나는 기계가 물리 세계(Physical World)를 어떻게 표현해야 하는가이다. 현재 시스템은 이미지(Image), 깊이 측정(Depth Measurement), 기하학적 지도(Geometric Map), 의미적 설명(Semantic Description), 학습된 잠재 표현(Latent Representation)을 결합하지만, 어떤 단일 접근법도 기하학(Geometry), 동역학(Dynamics), 인과관계(Causality), 불확실성(Uncertainty), 작업 관련성(Task Relevance)을 완전하게 포괄하지 못한다. 범용 물리 지능 시스템은 변화하는 환경과 다양한 시간 척도(Time Scale)에서 유용성을 유지하는 표현을 구축해야 한다.

월드 모델(World Model)은 예측 기반 물리 지능(Predictive Physical Intelligence)을 위한 유망한 기반을 제공하지만, 장기 시간 범위 예측(Long-Horizon Prediction)의 정확성을 확보하는 것은 여전히 어렵다. 움직임, 접촉력(Contact Force), 물체 상태(Object State), 환경 조건(Environmental Condition)에 대한 작은 추정 오차도 장기 예측 과정에서 누적될 수 있다. 월드 모델이 물리적 일관성(Physical Consistency)을 유지하고, 관측을 통해 가정을 갱신하며, 예측 가능한 동역학과 근본적으로 불확실한 사건을 구분하는 방법을 규명해야 한다.

물리적 인과관계(Physical Causality)는 또 다른 주요 한계이다. 물체를 인식한다는 것이 해당 물체를 밀거나, 들어 올리거나, 압축하거나, 떨어뜨렸을 때 어떻게 행동하는지 이해한다는 의미는 아니다. 로봇은 힘(Force), 재료(Material), 기하학(Geometry), 마찰(Friction), 운동(Motion) 사이의 관계를 학습하면서 자신의 행동이 초래하는 결과를 파악해야 한다. 반사실적 추론(Counterfactual Reasoning)을 지원하는 인과적 표현(Causal Representation)의 개발은 강건한 조작(Robust Manipulation)과 자율 계획(Autonomous Planning)에 필수적이다.

훈련 환경을 넘어서는 일반화(Generalization)는 피지컬 인공지능을 정의하는 핵심 과제 중 하나로 남아 있다. 실험실에서 훈련된 로봇은 실제 배치 환경에서 익숙하지 않은 조명, 표면 조건, 물체 배치, 인간 행동을 마주할 수 있다. 훈련 데이터와 실제 운영 데이터 사이의 통계적 유사성(Statistical Similarity)만으로는 안정적인 성능을 보장할 수 없다. 미래 시스템은 분포 변화(Distribution Shift)를 인식하고 새로운 상황마다 광범위한 재훈련(Retraining)을 수행하지 않고도 적응할 수 있어야 한다.

서로 다른 로봇 신체 간 전이(Cross-Embodiment Transfer)는 물리 지능이 다양한 신체 구조를 통해 구현되기 때문에 추가적인 어려움을 발생시킨다. 바퀴형 로봇(Wheeled Robot), 매니퓰레이터(Manipulator), 휴머노이드(Humanoid), 사족보행 로봇(Quadruped), 비행 로봇(Aerial Robot)은 서로 다른 구동 능력과 물리적 제약을 가진다. 연구자들은 어떤 지식이 서로 다른 신체 구조 사이에서 공유될 수 있으며, 어떤 지식이 형태 특화 적응(Morphology-Specific Adaptation), 제어 전략(Control Strategy), 물리적 경험(Physical Experience)을 필요로 하는지 규명해야 한다.

데이터 효율성(Data Efficiency)은 확장 가능한 로봇 학습(Scalable Robot Learning)을 가로막는 근본적인 장애물이다. 디지털 인공지능(Digital AI)과 달리 피지컬 인공지능은 장비, 에너지, 감독, 안전 조치에 상당한 비용이 발생하는 물리적 상호작용을 필요로 하는 경우가 많다. 대규모 로봇 경험 데이터를 경제적으로 수집하는 것이 항상 가능한 것은 아니다. 중요한 연구 방향은 제한된 시연(Demonstration), 희소 보상(Sparse Reward), 인간 영상(Human Video), 시뮬레이션(Simulation), 자율 상호작용(Autonomous Interaction)으로부터 재사용 가능한 물리 지식을 학습하는 것이다.

자기지도학습(Self-Supervised Learning)은 수작업으로 라벨링된 로봇 데이터셋(Robot Dataset)에 대한 의존도를 줄일 수 있지만, 가장 효과적인 학습 목표(Learning Objective)는 아직 명확하지 않다. 미래 관측 예측(Future Observation Prediction), 누락된 감각 정보 복원(Sensory Reconstruction), 잠재 동역학 추정(Latent Dynamics Estimation), 행동 조건부 상태 전이 학습(Action-Conditioned Transition Learning)은 서로 다른 형태의 학습 신호를 제공한다. 핵심 질문은 단순히 감각 정보를 정확하게 복원하는 것이 아니라 신뢰할 수 있는 제어를 지원하는 표현을 생성하는 학습 목표가 무엇인가이다.

지속 학습(Continual Learning)은 로봇이 수개월 또는 수년에 걸쳐 작동하면서 점점 더 중요해지는 문제를 제기한다. 물리 환경은 변화하고, 기계 부품은 마모되며, 새로운 작업이 등장하고, 이전에 학습한 행동은 더 이상 적합하지 않을 수 있다. 로봇은 가치 있는 기존 지식을 보존하면서 새로운 경험을 통합해야 한다. 안정적인 평생 학습(Lifelong Learning)을 실현하려면 기억 통합(Memory Consolidation), 선택적 적응(Selective Adaptation), 경험 검색(Experience Retrieval), 체계적인 지식 수정(Knowledge Revision)을 위한 메커니즘이 필요하다.

파국적 망각(Catastrophic Forgetting)은 시간이 지남에 따라 물리 지능을 축적하는 과정의 어려움을 보여준다. 새로운 조건에 맞추어 신경망 정책(Neural Policy)을 갱신하면 이전에 안정적으로 수행하던 능력이 의도치 않게 저하될 수 있다. 경험이 증가할수록 단순한 재훈련은 계산 비용이 커질 수 있다. 연구에서는 안정적인 지식(Stable Knowledge)과 빠르게 변화하는 정보(Rapidly Changing Information)를 분리하면서도 두 정보가 인식, 예측, 계획, 제어에 함께 영향을 미칠 수 있도록 하는 아키텍처(Architecture)를 확립해야 한다.

물리적 추론(Physical Reasoning)은 기호적 추론(Symbolic Reasoning)이나 텍스트 기반 추론(Textual Reasoning)만으로 수행하는 것보다 훨씬 복잡하다. 로봇은 의도한 행동이 기하학적으로 가능한지, 동역학적으로 안정적인지, 에너지 측면에서 실용적인지, 불확실성 아래에서 안전한지를 평가해야 한다. 의사결정이 지연되면 물리적 위험이 발생할 수 있으므로 추론은 실시간 제약(Real-Time Constraint)도 충족해야 한다. 따라서 숙고형 지능(Deliberative Intelligence)과 반응형 제어(Reactive Control)를 결합하는 것은 핵심적인 아키텍처 과제이다.

불확실성 추정(Uncertainty Estimation)은 신뢰할 수 있는 자율성(Dependable Autonomy)에 필수적이지만, 기존 접근법은 불완전한 지식과 예측할 수 없는 환경 행동을 구분하는 데 어려움을 겪는 경우가 많다. 로봇은 인식, 월드 모델, 계획된 행동, 예상 결과에 대한 신뢰도를 추정해야 한다. 신뢰할 수 있는 시스템은 예측이 충분하지 않은 상황을 인식하고, 추가 정보를 수집하거나, 지원을 요청하거나, 위험한 상황이 발생하기 전에 보수적인 운영 모드(Conservative Operating Mode)로 전환할 수 있어야 한다.

안전한 탐색(Safe Exploration)은 학습과 운영 신뢰성(Operational Reliability) 사이에 아직 해결되지 않은 긴장 관계를 형성한다. 자율 로봇은 상호작용을 통해 개선되지만, 실험 과정에서 장비를 손상시키거나 환경을 방해하거나 사람을 위험에 빠뜨릴 수 있다. 시뮬레이션은 더 안전한 학습 환경을 제공하지만, 시뮬레이션 동역학(Simulated Dynamics)이 현실을 완벽하게 재현할 수는 없다. 미래 연구는 정보 획득(Information Gain), 물리적 제약(Physical Constraint), 불확실성, 명시적으로 정의된 안전 경계(Safety Boundary)를 균형 있게 고려하는 탐색 전략을 개발해야 한다.

로봇 형태(Morphology)와 지능(Intelligence)의 관계 역시 더욱 깊이 있는 연구가 필요하다. 기계적 구조(Mechanical Structure)는 센서가 어떤 정보를 관측할 수 있는지, 액추에이터(Actuator)가 어떤 행동을 수행할 수 있는지, 환경의 힘이 행동에 어떤 영향을 미치는지를 결정한다. 지능은 물리적 신체와 독립적으로 최적화될 수 없다. 형태, 센싱(Sensing), 연산(Computation), 구동(Actuation), 학습 알고리즘(Learning Algorithm)을 공동 설계(Co-Design)하면 소프트웨어 최적화만으로는 달성하기 어려운 능력을 구현할 수 있다.

에너지 효율성(Energy Efficiency)은 또 다른 핵심적인 한계이다. 고급 신경망 모델(Neural Model)은 계산 자원을 필요로 하며, 이동(Locomotion)과 조작(Manipulation)은 상당한 전기적·기계적 에너지를 소비한다. 물리 지능 시스템은 센싱, 추론(Inference), 통신(Communication), 구동에 에너지를 적절히 배분해야 한다. 이벤트 기반 연산(Event-Driven Computation), 적응형 모델 실행(Adaptive Model Execution), 효율적인 하드웨어(Efficient Hardware), 에너지 인식 계획(Energy-Aware Planning)에 관한 연구는 지속적인 자율 운영에 필수적이다.

다중 로봇 지능(Multi-Robot Intelligence)은 개별 로봇의 성능 향상만으로 해결할 수 없는 문제를 제기한다. 대규모 로봇 군집(Fleet)은 작업을 조정하고, 경험을 공유하며, 일관된 환경 지식을 유지하고, 서로 충돌하는 관측 정보를 해결해야 한다. 통신 대역폭(Communication Bandwidth), 지연 시간(Latency), 개인정보 보호(Privacy), 이기종 로봇의 능력 차이(Heterogeneous Capabilities)는 집단 학습(Collective Learning)을 복잡하게 만든다. 확장 가능한 시스템은 어떤 지식을 로컬(Local)에 유지하고, 무엇을 공유하며, 집단적 의사결정의 신뢰성을 어떻게 보장할지 결정해야 한다.

평가 방법론(Evaluation Methodology)은 범용 물리 지능을 측정하기에 여전히 충분하지 않다. 제한된 조작 또는 내비게이션 벤치마크(Benchmark)에서의 성공이 적응성(Adaptability), 장기 신뢰성(Long-Term Reliability), 익숙하지 않은 환경에서의 능력을 의미하지는 않는다. 보다 포괄적인 평가는 전이 학습(Transfer Learning), 물리적 추론, 실패 복구(Failure Recovery), 안전성(Safety), 자원 효율성(Resource Efficiency), 다양한 작업과 신체 구조에 걸친 지속적인 성능(Sustained Performance)을 검토해야 한다.

장기 자율성(Long-Horizon Autonomy)은 개별적으로 평가되는 여러 능력을 통합해야 한다. 로봇이 뛰어난 인식, 정확한 단기 제어(Short-Term Control), 유능한 작업 계획(Task Planning)을 갖추고 있더라도 장시간 운영에서는 실패할 수 있다. 예상하지 못한 사건, 누적된 위치 추정 오차(Localization Error), 변화하는 목표, 기계적 성능 저하(Mechanical Degradation)는 서로 연결된 문제를 발생시킨다. 연구에서는 개별 모델의 성능만으로 자율성이 충분하다고 판단하기보다 시스템 수준의 신뢰성(System-Level Reliability)을 다루어야 한다.

파운데이션 모델(Foundation Model), 시각-언어-행동 시스템(Vision-Language-Action System), 월드 모델, 계층적 제어(Hierarchical Control)의 융합은 중요한 아키텍처적 질문을 제기한다. 범용 물리 지능이 통합된 엔드투엔드 모델(End-to-End Model)에서 주로 등장할지, 전문화된 구성 요소를 갖춘 모듈형 시스템(Modular System)에서 등장할지는 아직 불확실하다. 하이브리드 아키텍처(Hybrid Architecture)는 학습된 표현과 명시적 동역학(Explicit Dynamics), 기억(Memory), 계획(Planning), 안전 메커니즘(Safety Mechanism)을 결합할 수 있지만, 최적의 구성 방식은 여전히 해결되지 않았다.

또 다른 근본적인 질문은 물리적 경험(Physical Experience)과 추상적 지능(Abstract Intelligence)의 관계이다. 언어 기반 지식(Language-Based Knowledge)은 물리적 상호작용의 결과를 직접 경험하지 않고도 이를 설명할 수 있다. 반대로 체화 학습(Embodied Learning)은 현실에 기반한 지식(Grounded Knowledge)을 생성하지만, 작업 간 전이 능력이 제한될 수 있다. 기호적 추론, 잠재 월드 표현(Latent World Representation), 감각운동 경험(Sensorimotor Experience)이 어떻게 상호작용해야 하는지 이해하는 것은 미래의 범용 물리 인공지능(Physical AGI)을 위한 중요한 기반이 될 수 있다.

자기개선형 피지컬 인공지능(Self-Improving Physical AI) 시스템은 검증(Verification), 거버넌스(Governance), 운영 안정성(Operational Stability)에 관한 추가적인 연구 과제를 제기한다. 경험을 자율적으로 수집하고 정책을 갱신하는 로봇은 시간이 지남에 따라 성능을 향상시킬 수 있지만, 특정 환경에서의 개선이 다른 환경의 안전성을 보장하지는 않는다. 따라서 지속적인 배포(Continuous Deployment)를 위해서는 업데이트 평가(Update Evaluation), 성능 퇴행 탐지(Regression Detection), 검증된 능력 보존(Validated Capability Preservation), 새로운 행동 도입 통제(Behavior Introduction Control)를 위한 메커니즘이 필요하다.

핵심적인 미해결 과제는 단순히 더 많은 작업을 수행하는 로봇을 만드는 것이 아니다. 그것은 효율적으로 학습하고, 인과관계를 이해하며, 결과를 예측하고, 지식을 전이하며, 지속적으로 적응하고, 현실 세계의 제약 아래에서 안전하게 행동하는 물리 지능을 개발하는 것이다. 범용 물리 인공지능(Physical AGI)을 향한 진전은 이러한 능력을 하나의 시스템으로 통합하고, 신뢰성(Reliability), 일반화(Generalization), 자율성(Autonomy)을 재현 가능한 물리적 증거(Reproducible Physical Evidence)를 통해 입증하는 데 달려 있다.

## 07.02. Grounded World Representation

![](images/image2.png){width="7.268055555555556in" height="7.268055555555556in"}

현실 세계에 기반한 월드 표현(Grounded World Representation)은 지능적인 물리적 행동(Intelligent Physical Action)이 단순한 시각적 외형을 넘어 환경을 이해하는 능력에 의존하기 때문에 피지컬 인공지능(Physical AI)의 근본적인 요구사항이다. 로봇은 감각 관측(Sensory Observation)을 물리적 객체(Physical Entity), 공간적 관계(Spatial Relationship), 재료 특성(Material Property), 가능한 상호작용(Possible Interaction)과 연결해야 한다. 순수한 기호적 표현(Symbolic Representation)과 달리, 현실 세계에 기반한 표현은 측정 가능한 물리적 조건과 실제 행동의 결과에 일관되게 부합해야 한다.

전통적인 로봇 시스템(Traditional Robotic System)은 기하학적 지도(Geometric Map), 점유 격자(Occupancy Grid), 객체 모델(Object Model), 사전에 정의된 의미적 범주(Semantic Category)에 의존한다. 이러한 표현은 위치 추정(Localization), 내비게이션(Navigation), 조작(Manipulation)을 지원하지만, 환경의 일부 측면만 설명하는 경우가 많다. 기하학적 지도는 객체의 기능을 설명하지 않고 공간 구조만 표현할 수 있으며, 의미적 지도(Semantic Map)는 객체의 동적 행동(Dynamic Behavior)이나 물리적 제약(Physical Constraint)을 표현하지 않고 객체를 식별하는 데 그칠 수 있다.

현실 세계에 기반한 월드 표현은 기하학(Geometry), 의미 정보(Semantics), 동역학(Dynamics), 행동 가능성(Action Possibility)을 일관된 내부 모델(Internal Model)로 통합해야 한다. 기하학은 객체와 표면이 어디에 존재하는지를 설명하고, 의미 정보는 객체의 의미와 기능적 역할을 식별하며, 동역학은 상태가 어떻게 변화하는지를 설명한다. 행동 관련 정보(Action-Related Information)는 이러한 속성을 로봇의 능력과 연결하여 도달, 이동, 주행, 조작이 가능한 대상을 예측할 수 있도록 한다.

다중 모달 인식(Multimodal Perception)은 현실 세계에 기반한 표현을 위한 관측 기반(Observational Foundation)을 제공한다. 카메라(Camera)는 외형과 시각적 구조를 포착하고, 깊이 센서(Depth Sensor)는 공간적 관계를 추정하며, 라이다(LiDAR)는 환경의 기하학적 구조를 측정한다. 촉각 센서(Tactile Sensor), 힘 측정(Force Measurement), 고유수용감각(Proprioception), 관성 센싱(Inertial Sensing)은 시각만으로 얻을 수 없는 정보를 제공한다. 이러한 모달리티를 결합하면 개별 센서 측정보다 물리적으로 풍부한 정보를 포함하는 표현을 구축할 수 있다.

그러나 여러 센싱 모달리티(Sensing Modality)를 통합하는 과정에서는 보정(Calibration), 동기화(Synchronization), 불확실성(Uncertainty), 관측 불일치(Inconsistent Observation)와 관련된 문제가 발생한다. 서로 다른 센서는 각기 다른 주파수(Frequency), 해상도(Resolution), 잡음 수준(Noise Level)으로 작동한다. 현실 세계에 기반한 표현은 상충하는 측정값을 조정하면서 유용한 정보를 보존해야 한다. 또한 직접 관측된 속성, 추론된 속성, 아직 알려지지 않은 속성을 구분할 수 있어야 한다.

객체 중심 표현(Object-Centric Representation)은 물리적 환경이 지속적인 정체성(Persistent Identity)과 변화하는 상태(Changing State)를 가진 객체들로 구성되기 때문에 유망한 접근법이다. 로봇은 모든 관측을 독립적인 이미지로 처리하는 대신 객체의 위치, 속성, 관계에 대한 내부 설명을 유지할 수 있다. 이러한 표현은 객체 영속성(Object Permanence), 상호작용 추적(Interaction Tracking), 장애물 뒤에 일시적으로 가려진 객체에 대한 추론을 지원한다.

현실 세계에 기반한 이해에는 객체가 시각적 외형을 넘어서는 물리적 속성(Physical Property)을 가진다는 사실을 이해하는 것도 필요하다. 질량(Mass), 마찰(Friction), 강성(Stiffness), 유연성(Compliance), 표면 조건(Surface Condition)은 상호작용의 결과에 영향을 미친다. 이러한 속성은 직접 관측되지 않을 수 있으며 능동적 탐색(Active Exploration)을 필요로 하는 경우가 많다. 로봇은 움직임, 접촉(Contact), 힘 피드백(Force Feedback), 제어된 행동의 관측 결과를 통해 이러한 속성을 추론해야 한다.

행동 유도성 표현(Affordance Representation)은 환경 이해를 가능한 행동과 연결한다. 어떤 표면은 바퀴형 로봇(Wheeled Robot)이 주행할 수 있지만 무거운 적재물을 운반하는 다족보행 로봇(Legged Robot)에는 적합하지 않을 수 있다. 어떤 객체는 특정 말단 효과기(End Effector)로 파지할 수 있지만 다른 장치로는 접근할 수 없을 수 있다. 따라서 행동 유도성(Affordance)은 고정된 객체 라벨이 아니라 환경 속성, 로봇 형태(Morphology), 현재 상태(Current State), 의도된 작업(Intended Task) 사이의 관계로 표현되어야 한다.

공간적 현실 기반화(Spatial Grounding)는 여러 추상화 수준(Abstraction Level)에서 작동해야 한다. 국소 표현(Local Representation)은 충돌 회피(Collision Avoidance), 파지(Grasping), 정밀 운동 제어(Precise Motion Control)를 지원하고, 대규모 표현(Large-Scale Representation)은 내비게이션, 경로 선택(Route Selection), 작업 계획(Task Planning)을 지원한다. 포괄적인 시스템은 계량적 기하학(Metric Geometry)을 위상적 관계(Topological Relationship) 및 의미적 설명(Semantic Description)과 연결하여 서로 다른 공간 해상도(Spatial Resolution)에서도 정보의 일관성을 유지해야 한다.

시간적 현실 기반화(Temporal Grounding) 역시 물리적 환경이 지속적으로 변화하기 때문에 중요하다. 객체는 움직이고, 문은 열리고 닫히며, 표면에는 장애물이 생기고, 인간의 활동은 환경을 변화시킨다. 유용한 표현은 지속적인 속성(Persistent Property)과 일시적인 상태(Temporary State)를 구분하고 조건이 시간에 따라 어떻게 변화하는지에 대한 정보를 유지해야 한다. 이를 위해 시간적 기억(Temporal Memory), 상태 추정(State Estimation), 오래된 지식을 갱신하는 메커니즘이 필요하다.

월드 표현(World Representation)과 월드 모델링(World Modeling)의 관계는 특별히 주목할 필요가 있다. 월드 표현은 현재 또는 기억된 물리적 상태를 설명하는 반면, 예측 월드 모델(Predictive World Model)은 행동과 외부 영향에 따라 해당 상태가 어떻게 변화할지를 추정한다. 이 두 기능은 밀접하게 관련되어 있지만 동일하지는 않다. 현실 세계에 기반한 표현은 행동 조건부 예측(Action-Conditioned Prediction)과 계획(Planning)이 작동하는 데 필요한 상태 변수(State Variable)와 관계를 제공한다.

신경망(Neural Network)을 통해 학습된 잠재 표현(Latent Representation)은 복잡한 감각 정보를 압축된 내부 상태(Compact Internal State)로 변환할 기회를 제공한다. 그러나 압축성(Compactness)만으로 물리적 현실 기반화(Physical Grounding)가 보장되는 것은 아니다. 잠재 표현은 이미지를 정확하게 예측하면서도 접촉 추론(Contact Reasoning)이나 제어에 필요한 정보를 보존하지 못할 수 있다. 연구에서는 물리적으로 의미 있는 변수(Physically Meaningful Variable)를 유지하고 신뢰할 수 있는 후속 의사결정(Downstream Decision)을 지원하는 학습 목표(Learning Objective)를 규명해야 한다.

물리 법칙 기반 표현 학습(Physics-Informed Representation Learning)은 역학(Mechanics)과 환경 상호작용에서 도출된 구조적 제약(Structural Constraint)을 통합하여 일관성을 향상시킬 수 있다. 보존 법칙(Conservation Principle), 접촉 관계(Contact Relationship), 운동학적 제약(Kinematic Constraint), 운동 연속성(Motion Continuity)은 표현 학습을 안내할 수 있다. 그러나 실제 환경에는 불확실한 매개변수(Uncertain Parameter), 변형 가능한 재료(Deformable Material), 복잡한 상호작용이 존재하므로 엄격한 물리적 가정만으로 모든 상황을 설명하기는 어렵다.

인과적 현실 기반화(Causal Grounding)는 표현을 통계적 상관관계(Statistical Correlation) 이상으로 확장한다. 로봇은 객체들이 함께 움직인다는 사실뿐만 아니라 한 객체의 움직임이 다른 객체의 움직임을 유발하는지도 이해해야 한다. 개입(Intervention)은 제어된 행동에 따라 결과가 어떻게 달라지는지를 관측함으로써 물리적 관계에 대한 증거를 제공한다. 이러한 지식은 반사실적 추론(Counterfactual Reasoning)을 지원하여 로봇이 실제 행동을 실행하기 전에 대안적인 행동을 평가할 수 있도록 한다.

물리적 관측은 불완전하고 모호한 경우가 많기 때문에 불확실성(Uncertainty)을 명시적으로 표현해야 한다. 로봇은 객체의 존재를 알고 있더라도 정확한 위치, 재료, 안정성(Stability)을 알지 못할 수 있다. 불확실성을 숨기는 표현은 과도한 확신에 기반한 의사결정(Overconfident Decision)을 초래할 수 있다. 확률적 상태 추정(Probabilistic State Estimation), 신뢰도 측정(Confidence Measure), 복수의 경쟁 가설(Competing Hypothesis)은 확립된 지식과 불확실한 가정을 구분하는 데 도움이 된다.

부분 관측 가능성(Partial Observability)은 중요한 환경 상태를 직접 측정할 수 없을 때 추가적인 어려움을 발생시킨다. 가려진 객체(Occluded Object), 숨겨진 장애물(Hidden Obstacle), 내부 기계 상태(Internal Mechanical Condition), 알려지지 않은 인간의 의도(Unknown Human Intention)는 불완전한 증거를 바탕으로 추론해야 한다. 현실 세계에 기반한 표현은 숨겨진 상태(Hidden State)에 대한 불확실성을 유지하고, 중요한 결정을 내리기 전에 지식을 개선하는 정보 수집 행동(Information-Gathering Action)을 지원해야 한다.

기억(Memory)은 장시간 운영에서 현실 세계에 기반한 이해를 유지하는 데 핵심적인 역할을 한다. 단기 기억(Short-Term Memory)은 최근 관측과 빠르게 변화하는 상태를 보존하고, 장기 기억(Long-Term Memory)은 지속적인 기하학적 구조, 객체 특성, 학습된 동역학(Learned Dynamics), 이전 상호작용을 저장한다. 계층적 기억 아키텍처(Hierarchical Memory Architecture)는 즉각적인 감각운동 경험(Sensorimotor Experience)을 작업, 환경, 운영 기간에 걸쳐 축적된 지식과 연결할 수 있다.

물리적 지식은 환경과 로봇이 변화함에 따라 오래된 정보가 될 수 있으므로 지속적 표현 학습(Continual Representation Learning)이 필요하다. 로봇은 새로운 객체, 변경된 배치, 서로 다른 지형 조건(Terrain Condition), 점진적인 액추에이터 성능 저하(Actuator Degradation)를 경험할 수 있다. 내부 표현은 이전에 검증된 지식을 잃지 않으면서 적응해야 한다. 이는 안정적인 학습(Stable Learning), 선택적 기억 갱신(Selective Memory Update), 파국적 망각(Catastrophic Forgetting) 방지와 관련된 연구 과제를 제기한다.

서로 다른 로봇 신체 간 현실 기반화(Cross-Embodiment Grounding)는 서로 다른 로봇들이 동일한 물리적 환경에 대한 공통된 이해를 공유할 수 있는지에 관한 질문을 제기한다. 기하학과 객체 정체성(Object Identity)은 폭넓게 전이될 수 있지만, 도달 가능성(Reachability), 조작 가능성(Manipulability), 주행 가능성(Traversability)은 로봇의 신체 구조(Embodiment)에 따라 달라진다. 따라서 공유 월드 표현(Shared World Representation)은 신체 구조에 독립적인 환경 지식(Embodiment-Independent Environmental Knowledge)과 신체 구조 조건부 행동 및 능력 모델(Embodiment-Conditioned Action and Capability Model)의 결합을 필요로 할 수 있다.

언어 기반 현실화(Language Grounding)는 인간의 설명을 측정 가능한 물리적 상태와 실행 가능한 행동(Executable Action)에 연결함으로써 또 다른 계층을 추가한다. 깨지기 쉬운 물체를 안정적인 표면 위에 놓으라는 지시는 객체 정체성, 취약성(Fragility), 지지 관계(Support Relationship), 작업 제약(Task Constraint)에 대한 이해를 필요로 한다. 언어 모델(Language Model)만으로는 인식, 물리적 추론, 환경 피드백(Environmental Feedback)과의 신뢰할 수 있는 연결 없이 이러한 조건을 확립할 수 없다.

현실 세계에 기반한 표현의 평가(Evaluation)는 여전히 해결되지 않은 연구 문제이다. 재구성 정확도(Reconstruction Accuracy)와 객체 인식 점수(Object Recognition Score)는 유용한 측정값을 제공하지만, 해당 표현이 성공적인 물리적 상호작용을 지원하는지는 입증하지 못한다. 보다 의미 있는 평가는 예측 정확도(Prediction Accuracy), 인과적 일관성(Causal Consistency), 작업 전이(Task Transfer), 불확실성 보정(Uncertainty Calibration), 환경 변화에 대한 강건성(Robustness), 장기 자율 운영(Long-Horizon Autonomous Operation) 중의 성능을 검토해야 한다.

핵심적인 아키텍처 질문은 현실 세계에 기반한 월드 표현을 명시적으로 구조화(Explicitly Structured)해야 하는지, 완전히 학습(Entirely Learned)해야 하는지, 또는 하이브리드 접근법(Hybrid Approach)을 통해 구성해야 하는지에 관한 것이다. 명시적 구조(Explicit Structure)는 해석 가능성(Interpretability)을 제공하고 제약 기반 추론(Constraint-Based Reasoning)을 지원하는 반면, 학습된 표현(Learned Representation)은 고차원 관측(High-Dimensional Observation)에서 복잡한 패턴을 포착한다. 하이브리드 시스템(Hybrid System)은 객체 중심 상태 설명(Object-Centric State Description), 잠재 동역학(Latent Dynamics), 물리적 제약, 계층적 기억을 통합된 아키텍처(Unified Architecture) 안에서 결합할 수 있다.

궁극적으로 현실 세계에 기반한 월드 표현은 인식(Perception), 물리적 이해(Physical Understanding), 예측(Prediction), 추론(Reasoning), 행동(Action)을 연결하는 역할을 해야 한다. 목표는 단순히 환경에 대한 정확한 디지털 설명(Digital Description)을 구축하는 것이 아니라, 무엇이 존재하고, 어떻게 행동하며, 무엇이 불확실하고, 로봇이 무엇을 안전하게 수행할 수 있는지를 설명하는 행동 가능한 모델(Actionable Model)을 유지하는 것이다. 이러한 능력을 달성하는 것은 범용 피지컬 인공지능(General Physical AI)으로 나아가기 위한 근본적인 연구 과제이다.

## 07.03. Long Horizon World Model Prediction

![](images/image3.png){width="7.268055555555556in" height="7.268055555555556in"}

장기 시간 범위 월드 모델 예측(Long-Horizon World Model Prediction)은 자율 시스템(Autonomous System)이 장시간에 걸쳐 물리적 환경이 어떻게 변화하는지 예측해야 하기 때문에 피지컬 인공지능(Physical AI)의 근본적인 과제이다. 단기 예측(Short-Term Prediction)은 즉각적인 움직임과 접촉 결과를 추정할 수 있지만, 복잡한 작업은 수많은 미래 행동과 환경 변화에 걸친 추론을 필요로 한다. 신뢰할 수 있는 장기 예측은 불확실성(Uncertainty), 상호작용(Interaction), 변화하는 목표(Changing Objective)를 고려하면서 물리적 일관성(Physical Consistency)을 유지해야 한다.

월드 모델(World Model)은 행동(Action)과 외부 영향(External Influence)에 따라 환경 상태(Environmental State)가 어떻게 변화하는지를 추정함으로써 환경의 동역학(Dynamics)을 표현한다. 단기 예측에서는 관측을 통해 추정 상태를 자주 보정할 수 있으므로 작은 오차를 관리할 수 있다. 그러나 예측 시간 범위(Prediction Horizon)가 길어지면 예측 오차(Prediction Error)가 누적되어 점점 더 비현실적인 궤적(Unrealistic Trajectory)을 생성할 수 있다. 따라서 시간적 안정성(Temporal Stability)과 불확실성 관리(Uncertainty Management)는 필수적인 연구 과제가 된다.

장기 예측의 어려움은 부분적으로 물리 동역학(Physical Dynamics)의 비선형적 특성(Nonlinear Nature)에서 비롯된다. 접촉 사건(Contact Event), 마찰 변화(Friction Change), 충돌(Collision), 변형 가능한 재료(Deformable Material), 액추에이터 한계(Actuator Limitation)는 상태 사이에 불연속적인 전이(Discontinuous Transition)를 발생시킬 수 있다. 초기 조건(Initial Condition)의 작은 차이가 상당히 다른 결과로 이어질 수 있다. 따라서 예측 시스템은 하나의 결정론적 궤적(Deterministic Trajectory)을 가정하기보다 여러 가능한 미래(Multiple Plausible Futures)를 표현해야 한다.

시간적 추상화(Temporal Abstraction)는 긴 예측 시간 범위를 관리하기 위한 유망한 접근법이다. 모델은 모든 저수준 상태 전이(Low-Level State Transition)를 동일한 세부 수준으로 예측하는 대신 상위 수준의 사건(Event), 행동(Action), 주요 단계(Milestone)를 표현할 수 있다. 예를 들어 조작 작업(Manipulation Task)은 객체 접근(Approach), 접촉 형성(Contact Establishment), 들어 올리기(Lifting), 운반(Transport), 배치(Placement)로 구성될 수 있다. 이러한 단계는 효율적인 예측과 계획을 위한 의미 있는 시간적 구조(Temporal Structure)를 제공한다.

계층적 월드 모델(Hierarchical World Model)은 여러 시간 척도(Multiple Timescales)에 걸쳐 예측을 구성할 수 있다. 고속 동역학 모델(Fast Dynamics Model)은 즉각적인 움직임, 접촉력(Contact Force), 제어 응답(Control Response)을 추정하고, 중간 수준 모델(Intermediate Model)은 객체 상호작용(Object Interaction)과 작업 진행(Task Progression)을 표현한다. 장기 모델(Long-Term Model)은 목표(Goal), 환경 변화(Environmental Change), 지속적인 결과(Persistent Consequence)를 포착한다. 이러한 계층을 조정하면 로봇은 모든 과정을 동일하게 상세하게 시뮬레이션하지 않고도 장시간에 걸친 추론을 수행할 수 있다.

잠재 동역학 모델(Latent Dynamics Model)은 압축된 표현 공간(Compressed Representation Space)에서 미래 상태를 예측하는 또 다른 접근법을 제공한다. 모델은 매 단계에서 완전한 이미지나 기하학적 재구성(Geometric Reconstruction)을 생성하는 대신 압축된 잠재 상태(Compact Latent State) 사이의 전이를 추정할 수 있다. 이는 계산 요구량(Computational Requirement)을 줄이지만, 학습된 표현은 물리적 실현 가능성(Physical Feasibility), 접촉 동역학(Contact Dynamics), 안전성(Safety), 작업 완료(Task Completion)에 필요한 정보를 보존해야 한다.

행동 조건부 예측(Action-Conditioned Prediction)은 미래의 물리적 상태가 로봇이 선택하는 행동에 따라 달라지기 때문에 필수적이다. 월드 모델은 서로 다른 제어 명령(Control Command), 조작 전략(Manipulation Strategy), 내비게이션 결정(Navigation Decision)이 이후 결과에 어떤 영향을 미치는지 추정해야 한다. 이러한 능력은 모델 기반 계획(Model-Based Planning)과 반사실적 평가(Counterfactual Evaluation)를 지원한다. 그러나 이전에 관측한 행동과 다른 행동 시퀀스(Action Sequence)를 평가할 때에도 예측 정확도(Prediction Accuracy)가 신뢰할 수 있는 수준으로 유지되어야 한다.

예측이 미래로 더 멀리 확장될수록 불확실성(Uncertainty)은 증가한다. 센서 잡음(Sensor Noise), 알려지지 않은 물리적 매개변수(Unknown Physical Parameter), 환경 교란(Environmental Disturbance), 예측하기 어려운 인간 행동(Unpredictable Human Action)은 다양한 불확실성의 원인이 된다. 장기 예측 모델은 불완전한 지식(Incomplete Knowledge)에서 발생하는 불확실성과 환경 자체에 내재된 변동성(Inherent Variability)을 구분해야 한다. 이러한 구분이 없다면 기반 가정이 신뢰할 수 없는 상황에서도 예측 궤적이 지나치게 정밀한 것처럼 나타날 수 있다.

확률적 월드 모델(Probabilistic World Model)은 확률 분포(Probability Distribution), 앙상블(Ensemble), 샘플링된 궤적(Sampled Trajectory)을 통해 대안적인 미래 결과(Alternative Future Outcome)를 표현할 수 있다. 이러한 접근법은 계획 시스템(Planner)이 여러 가능한 시나리오(Scenario)에 걸쳐 위험을 평가할 수 있도록 한다. 그러나 예측 시간 범위가 증가하면 다양한 예측을 유지하는 데 필요한 계산 비용이 커진다. 따라서 비현실적으로 많은 미래 가능성을 생성하지 않으면서 의미 있는 불확실성을 보존하는 효율적인 방법이 필요하다.

예측 드리프트(Prediction Drift)는 지속적인 자율성(Sustained Autonomy)을 가로막는 주요 장애물이다. 월드 모델이 자신이 예측한 상태를 반복적으로 입력으로 사용하면 작은 오차가 누적되어 시뮬레이션된 미래가 물리적으로 타당한 행동에서 점차 벗어날 수 있다. 이 문제는 접촉이 많은 조작(Contact-Rich Manipulation)과 복잡한 내비게이션(Complex Navigation)에서 특히 심각해진다. 학습 방법은 단일 단계 예측 정확도(One-Step Prediction Accuracy)만 최적화하는 것이 아니라 다단계 일관성(Multi-Step Consistency)을 향상시켜야 한다.

폐루프 예측(Closed-Loop Prediction)은 실행 과정에서 새로운 관측을 통합함으로써 누적 오차를 줄일 수 있다. 로봇은 고정된 장기 예측(Fixed Long-Term Forecast)에 의존하는 대신 추정 상태(Estimated State)를 주기적으로 갱신하고 재계획(Replanning)을 수행한다. 이러한 접근법은 월드 모델링(World Modeling)을 모델 예측 제어(Model Predictive Control) 및 이동 시간 범위 계획(Receding-Horizon Planning)과 연결한다. 그러나 빈번한 재계획은 계산 비용을 증가시키고, 연속된 예측 사이에 큰 불일치가 발생하면 불안정한 행동을 유발할 수 있다.

물리적 제약(Physical Constraint)은 예측을 물리적으로 타당한 상태 전이(Plausible State Transition)로 제한함으로써 장기 일관성(Long-Horizon Consistency)을 향상시킬 수 있다. 보존 법칙(Conservation Law), 운동학적 관계(Kinematic Relationship), 충돌 제약(Collision Constraint), 접촉 역학(Contact Mechanics)은 유용한 구조적 지침(Structural Guidance)을 제공한다. 물리 법칙 기반 학습(Physics-Informed Learning)은 이러한 제약을 데이터 기반 동역학 추정(Data-Driven Dynamics Estimation)과 결합할 수 있다. 그러나 불확실한 재료 특성, 복잡한 마찰, 모델링되지 않은 상호작용을 다루기 위해서는 엄격한 물리적 가정만이 아닌 유연한 표현이 필요하다.

인과적 추론(Causal Reasoning)은 긴 행동 시퀀스(Action Sequence)에 걸친 결과를 예측할 때 점점 더 중요해진다. 로봇은 초기 결정(Early Decision)이 이후의 기회(Opportunity), 위험(Risk), 환경 조건(Environmental Condition)에 어떤 영향을 미치는지 이해해야 한다. 장애물을 이동시키면 내비게이션이 가능해질 수 있지만, 객체를 잘못 배치하면 후속 조작(Subsequent Manipulation)이 불가능해질 수 있다. 인과적 월드 모델(Causal World Model)은 행동과 지연된 결과(Delayed Outcome) 사이의 의미 있는 의존 관계를 유지하는 예측을 지원할 수 있다.

기억(Memory)은 현재 관측보다 훨씬 이전에 발생한 정보가 중요할 수 있기 때문에 장기 예측에 필수적이다. 로봇은 이전 객체 위치(Previous Object Location), 완료된 하위 작업(Completed Subtask), 환경 변화(Environmental Change), 과거 상호작용 실패(Interaction Failure)를 기억해야 할 수 있다. 단기 기억(Short-Term Memory)은 즉각적인 상태 추정(State Estimation)을 지원하고, 장기 기억(Long-Term Memory)은 지속적인 지식(Persistent Knowledge)을 보존한다. 계층적 기억 시스템(Hierarchical Memory System)은 여러 예측 시간 범위에 걸쳐 이러한 표현을 연결할 수 있다.

지속적인 월드 상태 추정(Persistent World State Estimation)은 일시적인 관측(Temporary Observation)과 지속적인 환경 속성(Durable Environmental Property)을 구분해야 한다. 이전에 열려 있던 문은 나중에 닫힐 수 있지만, 구조적인 벽(Structural Wall)은 일반적으로 고정된 상태를 유지한다. 예측 모델은 안정적인 지식을 불필요하게 폐기하지 않으면서 동적 상태(Dynamic State)를 갱신해야 한다. 이를 위해 객체 정체성(Object Identity), 시간적 유효성(Temporal Validity), 환경 지속성(Environmental Persistence), 관측되지 않은 변화에 대한 불확실성을 추적하는 표현이 필요하다.

장기 예측은 인간 행동(Human Behavior)과 다중 에이전트 상호작용(Multi-Agent Interaction)에 대한 이해에도 의존한다. 인간과 다른 로봇은 목표를 변경하거나 자율 시스템에 반응하거나 예상하지 못한 교란을 발생시킬 수 있다. 이러한 행동을 결정론적 물리 동역학(Deterministic Physical Dynamics)만으로 항상 모델링할 수는 없다. 예측 시스템은 미래 의도(Future Intention)에 대한 정당화되지 않은 가정을 피하면서 물리적 제약과 불확실한 행동 모델(Uncertain Behavioral Model)을 결합해야 한다.

장기 월드 모델을 활용한 계획(Planning)은 예측의 세부 수준(Predictive Detail)과 계산 효율성(Computational Efficiency) 사이의 균형을 필요로 한다. 가능한 모든 행동 시퀀스를 고해상도 시뮬레이션(High-Resolution Simulation)으로 평가하는 것은 빠르게 비현실적이 된다. 계층적 계획(Hierarchical Planning), 궤적 샘플링(Trajectory Sampling), 학습된 가치 함수(Learned Value Function), 선택적 시뮬레이션(Selective Simulation)은 이러한 부담을 줄일 수 있다. 핵심 연구 질문은 의사결정에 가장 큰 영향을 미치는 미래 사건에 계산 자원을 어떻게 배분할 것인가이다.

적응형 예측 시간 범위(Adaptive Prediction Horizon)는 모델이 얼마나 먼 미래를 어느 정도의 정밀도로 예측할지를 변화시키는 잠재적인 해결책을 제공한다. 즉각적이고 위험도가 높은 상호작용(High-Risk Interaction)은 상세한 단기 시뮬레이션(Short-Term Simulation)을 필요로 하지만, 먼 미래의 목표(Distant Objective)는 추상적 상태 전이(Abstract State Transition)로 표현할 수 있다. 예측 깊이(Prediction Depth)는 불확실성과 작업 복잡도(Task Complexity)에 따라 달라질 수도 있다. 이러한 접근법은 안전한 의사결정에 필요한 정보를 보존하면서 효율성을 향상시킬 수 있다.

장기 동역학 학습(Long-Horizon Dynamics Learning)은 의미 있는 물리적 상호작용의 확장된 시퀀스를 포착하는 훈련 데이터(Training Data)를 필요로 한다. 짧은 시연(Short Demonstration)은 개별 행동을 설명할 수 있지만, 지연된 결과(Delayed Consequence), 복구 전략(Recovery Strategy), 지속적인 환경 변화(Persistent Environmental Change)를 드러내지 못할 수 있다. 긴 궤적(Long Trajectory)을 수집하는 데는 높은 비용이 발생하며, 동기화(Synchronization), 데이터 품질(Data Quality), 희귀 사건(Rare Event)과 관련된 문제가 수반된다. 시뮬레이션과 플릿 규모 경험(Fleet-Scale Experience)은 데이터 범위를 확대하는 데 도움이 될 수 있다.

자기지도학습(Self-Supervised Learning)은 광범위한 수동 주석(Manual Annotation) 없이 시간적 구조(Temporal Structure)를 학습할 기회를 제공한다. 모델은 미래 잠재 상태(Future Latent State)를 예측하거나, 사건 경계(Event Boundary)를 식별하거나, 누락된 관측(Missing Observation)을 복원하거나, 행동 결과(Action Consequence)를 추정할 수 있다. 그러나 예측 유사성(Predictive Similarity)을 최적화하는 것이 반드시 계획에 유용한 표현(Planning Representation)을 생성하는 것은 아니다. 학습 목표(Learning Objective)는 제어 가능성(Controllability), 물리적 제약, 인과적 의존성(Causal Dependency), 작업 관련 정보(Task-Relevant Information)의 보존을 장려해야 한다.

장기 월드 모델의 평가(Evaluation)는 시각적 예측 품질(Visual Prediction Quality)을 넘어 확장되어야 한다. 모델은 현실적인 미래 관측(Future Observation)을 생성하면서도 객체 안정성(Object Stability), 충돌 결과(Collision Outcome), 작업 실현 가능성(Task Feasibility)을 잘못 예측할 수 있다. 의미 있는 평가는 점점 더 긴 운영 시간 범위(Operational Horizon)에 걸쳐 다단계 물리적 일관성(Multi-Step Physical Consistency), 불확실성 보정(Uncertainty Calibration), 행동 조건부 정확도(Action-Conditioned Accuracy), 계획 효과성(Planning Effectiveness), 예측 실패 복구(Prediction Failure Recovery)를 측정해야 한다.

중요한 아키텍처적 질문(Architectural Question)은 월드 모델을 파운데이션 모델(Foundation Model), 추론 시스템(Reasoning System), 저수준 제어기(Low-Level Controller)와 어떻게 통합할 것인가에 관한 것이다. 범용 모델(General-Purpose Model)은 의미적 이해(Semantic Understanding)와 작업 수준 예측(Task-Level Prediction)을 제공할 수 있으며, 전문화된 동역학 모델(Specialized Dynamics Model)은 정밀한 물리적 상호작용을 처리할 수 있다. 계층적 아키텍처(Hierarchical Architecture)는 공유 상태 표현(Shared State Representation), 기억, 피드백(Feedback)을 통해 이러한 능력을 조정할 수 있지만, 최적의 구성 방식은 여전히 해결되지 않았다.

궁극적으로 장기 시간 범위 월드 모델 예측은 단순히 단기 예측(Short-Term Forecasting)을 더 많은 시간 단계(Time Step)로 확장하는 문제가 아니다. 이를 위해서는 시간적 추상화(Temporal Abstraction), 인과적 이해(Causal Understanding), 지속적 기억(Persistent Memory), 불확실성 인식 추론(Uncertainty-Aware Reasoning), 물리적으로 일관된 동역학(Physically Consistent Dynamics), 상호작용을 통한 지속적인 보정(Continuous Correction)이 필요하다. 이러한 과제를 해결하면 피지컬 인공지능 시스템은 지연된 결과를 예측하고, 복잡한 작업을 계획하며, 장시간에 걸쳐 신뢰할 수 있는 자율 행동(Reliable Autonomous Behavior)을 지속할 수 있게 될 것이다.

## 07.04. Physical Causality and Commonsense

![](images/image4.png){width="7.268055555555556in" height="7.268055555555556in"}

물리적 인과관계(Physical Causality)와 상식적 이해(Commonsense)는 지능형 로봇이 환경에 무엇이 존재하는지만이 아니라 물리적 사건이 왜 발생하는지도 이해해야 하므로 피지컬 인공지능(Physical AI)의 근본적인 요구사항이다. 객체를 인식하고 움직임을 예측하는 것만으로는 행동과 결과를 연결하는 메커니즘(Mechanism)을 이해하기에 충분하지 않다. 물리 지능(Physical Intelligence)은 이전에 관측하지 못한 상황에서도 신뢰할 수 있는 상호작용(Interaction), 적응(Adaptation), 추론(Reasoning)을 지원하는 인과적 지식(Causal Knowledge)을 필요로 한다.

물리적 인과관계(Physical Causality)는 힘(Force), 움직임(Motion), 접촉(Contact), 환경 조건(Environmental Condition)이 물리적 상태(Physical State)의 변화를 일으키는 관계를 의미한다. 로봇이 객체를 밀었을 때 발생하는 움직임은 질량(Mass), 마찰(Friction), 가해진 힘(Applied Force), 표면 기하학(Surface Geometry), 외부 제약(External Constraint)에 따라 달라진다. 인과관계를 이해하는 시스템은 이러한 메커니즘을 표면적인 상관관계(Superficial Correlation)와 구분하고, 어떤 변수가 상호작용의 결과를 결정하는지 식별해야 한다.

물리적 상식(Physical Commonsense)은 일상적인 객체와 환경이 어떻게 행동하는지에 관한 실용적 지식(Practical Knowledge)을 의미한다. 인간은 지지되지 않은 객체가 떨어지고, 깨지기 쉬운 재료가 과도한 힘에 의해 파손되며, 불안정한 구조물이 붕괴할 수 있다는 사실을 직관적으로 예상한다. 로봇 역시 효과적으로 작동하기 위해 이와 유사한 예측 능력을 습득해야 한다. 그러나 물리적 행동은 재료(Material), 기하학(Geometry), 환경 조건에 따라 달라지므로 상식적 지식은 상황적 맥락(Context)에 민감하게 적용되어야 한다.

핵심적인 과제는 통계적 예측(Statistical Prediction)과 인과적 이해(Causal Understanding)를 구분하는 것이다. 방대한 영상으로 훈련된 모델은 떨어지는 객체가 바닥에 도달할 것이라고 예측할 수 있지만, 그 기반에 있는 중력 상호작용(Gravitational Interaction)을 이해하지 못할 수 있다. 이러한 예측은 비정상적인 힘이나 제약이 도입되면 실패할 수 있다. 인과적 표현(Causal Representation)은 관련된 물리적 변수를 변경했을 때 결과적인 행동이 어떻게 달라지는지를 설명할 수 있어야 한다.

개입(Intervention)은 물리적 인과관계를 학습하기 위한 강력한 메커니즘을 제공한다. 로봇은 사건을 수동적으로 관측하는 대신 객체를 밀고, 당기고, 들어 올리고, 회전시키고, 놓아보면서 속성을 조사할 수 있다. 제어된 상호작용(Controlled Interaction)은 행동, 힘, 결과 사이의 관계를 드러낸다. 이러한 능동 학습(Active Learning) 과정은 시스템이 가설(Hypothesis)을 검증하고, 수동적 관측(Passive Observation)만으로는 신뢰성 있게 구분하기 어려운 여러 설명을 판별할 수 있도록 한다.

반사실적 추론(Counterfactual Reasoning)은 실제로 수행하지 않은 행동의 결과를 고려함으로써 인과적 이해를 확장한다. 로봇은 용기를 기울이면 내용물이 쏟아질지, 객체의 지지대를 제거하면 떨어질지, 다른 파지 방법(Grasp Strategy)을 사용하면 미끄러짐을 방지할 수 있을지를 평가할 수 있다. 이러한 추론은 실제 물리적 행동을 실행하기 전에 가능한 결과를 비교할 수 있도록 하여 계획(Planning)을 지원한다.

객체 영속성(Object Permanence)과 지속성(Persistence)은 물리적 상식의 중요한 구성 요소이다. 로봇은 객체가 일시적으로 가려지더라도 계속 존재하며, 일반적으로 관측 사이에 물리적 속성이 유지된다는 사실을 이해해야 한다. 그러나 객체의 상태(Object State)는 관측되지 않은 상호작용을 통해 변화할 수 있다. 따라서 신뢰할 수 있는 추론은 지속적인 객체 정체성(Persistent Object Identity)을 위치(Location), 방향(Orientation), 손상(Damage), 환경 변화(Environmental Change)에 대한 불확실성과 결합해야 한다.

지지 관계(Support Relationship)는 인과적 지식의 또 다른 필수 범주이다. 객체는 지지 표면(Supporting Surface)과 접촉력(Contact Force)이 중력의 영향을 균형 있게 상쇄할 때 안정적으로 유지된다. 지지대를 제거하면 낙하(Falling), 미끄러짐(Sliding), 회전(Rotation)이 발생할 수 있다. 조작(Manipulation)이나 적재(Stacking) 작업을 수행하는 로봇은 시각적 외형에만 의존하지 않고 하중 분포(Load Distribution), 질량 중심(Center of Mass), 접촉 기하학(Contact Geometry), 구조적 안정성(Structural Stability)을 추론해야 한다.

접촉 역학(Contact Mechanics)은 물리적 상호작용에서 불연속적인 상태 전이(Discontinuous Transition)가 자주 발생하기 때문에 상당한 복잡성을 초래한다. 객체는 힘과 재료 특성(Material Property)에 따라 달라붙거나, 미끄러지거나, 튀어 오르거나, 변형되거나, 파손될 수 있다. 접촉 조건(Contact Condition)의 작은 변화도 결과적인 움직임을 크게 바꿀 수 있다. 피지컬 인공지능은 실시간 의사결정(Real-Time Decision-Making)에 필요한 계산 효율성(Computational Efficiency)을 유지하면서 이러한 전이를 포착하는 표현을 학습해야 한다.

재료 이해(Material Understanding)는 인과적 추론과 밀접하게 관련되어 있다. 금속(Metal), 유리(Glass), 직물(Fabric), 고무(Rubber), 액체(Liquid)는 힘과 환경 조건에 서로 다르게 반응한다. 시각적 외형은 부분적인 단서를 제공하지만, 재료 특성은 촉각 센싱(Tactile Sensing)과 상호작용을 통해 확인해야 하는 경우가 많다. 로봇은 적절한 조작 전략(Manipulation Strategy)을 선택하고 객체 손상을 방지하기 위해 강성(Stiffness), 마찰(Friction), 탄성(Elasticity), 취약성(Fragility), 변형 거동(Deformation Behavior)을 추정해야 한다.

인간의 물리적 상식은 정확한 수치 시뮬레이션(Numerical Simulation)보다 정성적 추론(Qualitative Reasoning)을 활용하는 경우가 많다. 사람은 상세한 힘 방정식(Force Equation)을 계산하지 않고도 무거운 객체를 들어 올리기 어렵거나 폭이 좁은 적재 구조물이 불안정해질 수 있음을 인식한다. 로봇 역시 더 무겁다(Heavier), 더 부드럽다(Softer), 더 안정적이다(More Stable), 더 미끄럽다(More Slippery)와 같은 관계를 포착하는 정성적 표현(Qualitative Representation)의 이점을 활용하면서 필요할 때 정밀한 동역학(Precise Dynamics)을 사용할 수 있어야 한다.

정성적 상식(Qualitative Commonsense)과 정량적 물리학(Quantitative Physics)을 결합하는 것은 여전히 해결되지 않은 연구 과제이다. 기호적 설명(Symbolic Description)은 해석 가능한 관계(Interpretable Relationship)를 제공하고 추상적 계획(Abstract Planning)을 지원하는 반면, 수치 모델(Numerical Model)은 힘, 궤적(Trajectory), 접촉 동역학(Contact Dynamics)을 추정한다. 어느 한 접근법만으로 모든 상황을 해결하기는 어렵다. 하이브리드 아키텍처(Hybrid Architecture)는 정성적 인과 규칙(Qualitative Causal Rule)을 학습된 동역학 모델(Learned Dynamics Model) 및 물리 기반 시뮬레이션(Physics-Based Simulation)과 연결하여 유연한 물리적 추론을 지원할 수 있다.

인과적 월드 모델(Causal World Model)은 물리적 상태가 어떻게 변화하는지만이 아니라 특정 상태 전이가 왜 발생하는지도 표현하는 것을 목표로 한다. 이러한 모델은 로봇 행동(Robot Action)의 영향과 환경 교란(Environmental Disturbance), 숨겨진 변수(Hidden Variable)의 영향을 구분해야 한다. 인과적 의존성(Causal Dependency)을 명시적 또는 암묵적으로 표현함으로써 변화하는 조건에서 예측 성능을 향상시키고, 훈련 사례와 다른 익숙하지 않은 상호작용에 대한 추론을 지원할 수 있다.

인간 영상(Human Video)으로부터 물리적 상식을 학습하는 것은 대규모 지식 획득(Large-Scale Knowledge Acquisition)의 기회를 제공한다. 영상에는 객체 움직임(Object Motion), 도구 사용(Tool Use), 재료 상호작용(Material Interaction), 인간의 조작 전략(Human Manipulation Strategy)에 관한 사례가 포함되어 있다. 그러나 시각적 관측만으로는 정확한 힘, 숨겨진 제약, 대안적인 결과를 파악하기 어렵다. 따라서 수동적 영상으로 훈련된 모델은 인과적 모호성(Causal Ambiguity)을 해결해야 하며, 학습된 가정을 검증하기 위해 물리적 상호작용이 필요할 수 있다.

시뮬레이션(Simulation)은 물리적 매개변수(Physical Parameter)와 개입을 체계적으로 변경할 수 있으므로 인과관계를 연구하기 위한 통제된 환경(Controlled Environment)을 제공한다. 로봇은 실제 장비를 위험에 노출시키지 않고 질량, 마찰, 중력(Gravity), 접촉 조건, 객체 기하학(Object Geometry)의 변화를 조사할 수 있다. 그러나 시뮬레이션된 상호작용은 불완전한 물리 모델(Physics Model)에 의존하므로 시뮬레이션에서 획득한 지식은 실제 세계의 행동(Real-World Behavior)을 통해 검증되어야 한다.

불확실성(Uncertainty)은 물리적 인과 추론(Physical Causal Reasoning)과 분리할 수 없다. 로봇은 객체를 밀면 미끄러질 가능성이 높다는 사실을 알더라도 정확한 마찰계수(Friction Coefficient)는 알지 못할 수 있다. 이용 가능한 관측과 일치하는 여러 인과적 설명(Causal Explanation)이 동시에 존재할 수도 있다. 신뢰할 수 있는 시스템은 대안적인 가설(Alternative Hypothesis)을 유지하고, 신뢰도(Confidence)를 추정하며, 불확실성이 안전성이나 작업 성공(Task Success)에 상당한 영향을 미칠 수 있을 때 정보 수집 행동(Information-Gathering Action)을 선택해야 한다.

장기 작업(Long-Horizon Task)은 서로 의존하는 행동 시퀀스(Action Sequence)에 걸친 인과적 추론을 필요로 한다. 하나의 객체를 이동시키면 다른 객체가 드러날 수 있고, 문을 열면 내비게이션 가능성(Navigational Possibility)이 달라질 수 있으며, 부품을 잘못 배치하면 이후 조립(Assembly)이 불가능해질 수 있다. 물리적 상식은 로봇이 이러한 지연된 결과(Delayed Consequence)를 예측하도록 돕는다. 따라서 인과적 계획(Causal Planning)은 즉각적인 상호작용을 미래 작업 제약(Future Task Constraint) 및 변화하는 환경 상태(Evolving Environmental State)와 연결해야 한다.

신체 구조(Embodiment)는 인과적 지식이 획득되고 적용되는 방식에 영향을 미친다. 바퀴형 로봇(Wheeled Robot), 휴머노이드(Humanoid), 매니퓰레이터(Manipulator), 비행 로봇(Aerial Robot)은 서로 다른 센서(Sensor)와 액추에이터(Actuator)를 통해 물리적 환경과 상호작용한다. 기본적인 물리 법칙(Physical Law)은 공통으로 적용되지만, 수행 가능한 개입과 관측 가능한 결과는 서로 다르다. 연구에서는 각 로봇의 고유한 물리적 능력(Physical Capability)을 고려하면서 인과적 지식을 서로 다른 신체 구조 사이에 어떻게 전이할 수 있는지 규명해야 한다.

언어 모델(Language Model)과 파운데이션 모델(Foundation Model)은 일상적인 물리적 관계에 관한 폭넓은 설명을 제공할 수 있지만, 언어적 친숙성(Linguistic Familiarity)이 현실 세계에 기반한 인과적 능력(Grounded Causal Competence)을 보장하지는 않는다. 모델은 깨지기 쉬운 객체를 들어 올리는 방법을 정확하게 설명하면서도 안전한 조작에 필요한 힘을 추정하지 못할 수 있다. 따라서 물리적 상식은 감각적 증거(Sensory Evidence), 행동 조건부 예측(Action-Conditioned Prediction), 실제 상호작용에서 얻은 피드백(Feedback)과 연결되어야 한다.

물리적 인과관계의 평가(Evaluation)는 객체 인식(Object Recognition)과 기존의 예측 정확도(Prediction Accuracy)를 넘어 확장되어야 한다. 시스템은 개입(Intervention), 반사실적 질문(Counterfactual Question), 익숙하지 않은 재료 특성(Unfamiliar Material Property), 변화하는 물리적 매개변수(Changing Physical Parameter), 다단계 조작 작업(Multi-Step Manipulation Task)을 통해 검증되어야 한다. 강력한 평가는 근본적인 인과 메커니즘(Causal Mechanism)이 유지되는 상태에서 표면적인 시각적 상관관계가 변경되더라도 학습된 지식이 유효하게 유지되는지를 확인해야 한다.

안전성(Safety)은 인과적 이해(Causal Understanding)가 필요한 실질적인 이유를 제공한다. 인간, 장비, 취약한 기반시설(Fragile Infrastructure) 주변에서 작동하는 로봇은 자신의 행동이 어떻게 유해한 결과(Harmful Consequence)를 발생시킬 수 있는지 예측해야 한다. 인과적 추론은 불안정한 객체(Unstable Object), 과도한 힘(Excessive Force), 위험한 접촉 조건(Dangerous Contact Condition), 움직임의 간접적 영향(Indirect Effect)을 식별하는 데 도움이 된다. 그러나 인과 모델 자체에도 불확실성이 존재하므로 모니터링(Monitoring), 제약(Constraint), 보호 제어 메커니즘(Protective Control Mechanism)과 결합되어야 한다.

중요한 미해결 질문은 물리적 상식이 주로 대규모 예측 학습(Large-Scale Predictive Learning)에서 출현해야 하는지, 아니면 명시적 인과 구조(Explicit Causal Structure)와 능동적 실험(Active Experimentation)을 필요로 하는지에 관한 것이다. 예측 모델(Predictive Model)은 광범위한 규칙성(Regularity)을 포착하는 반면, 구조화된 인과 모델(Structured Causal Model)은 개입과 설명(Explanation)을 지원한다. 미래 아키텍처는 두 접근법을 체화된 경험(Embodied Experience)과 통합하여 로봇이 제어된 물리적 상호작용을 통해 추상적 지식(Abstract Knowledge)을 정교하게 개선할 수 있도록 할 것이다.

궁극적으로 물리적 인과관계(Physical Causality)와 상식적 이해(Commonsense)는 패턴 인식(Pattern Recognition)에서 진정한 물리적 이해(Genuine Physical Understanding)로 발전하기 위한 기반을 제공한다. 로봇은 객체가 왜 특정 방식으로 행동하는지, 행동이 결과를 어떻게 변화시키는지, 불확실성 아래에서 어떤 결과가 가능한지를 학습해야 한다. 인과적 표현(Causal Representation), 능동적 실험(Active Experimentation), 반사실적 추론(Counterfactual Reasoning), 현실 세계에 기반한 물리 지식(Grounded Physics)의 발전은 적응 가능하고(Adaptable), 신뢰할 수 있으며(Reliable), 점차 범용성을 갖추는 피지컬 인공지능(Physical AI) 시스템을 개발하는 데 필수적이다.

## 07.05. Real World Generalization

![](images/image5.png){width="7.268055555555556in" height="7.268055555555556in"}

실제 세계 일반화(Real-World Generalization)는 로봇이 훈련 과정에서 경험한 환경과 작업을 넘어 신뢰성 있게 작동해야 하므로 피지컬 인공지능(Physical AI)에서 가장 중요한 미해결 과제 중 하나이다. 실험실에서 성공적으로 작동하는 시스템도 익숙하지 않은 객체, 조명, 지형 또는 인간 행동에 노출되면 실패할 수 있다. 일반화(Generalization)는 광범위한 재훈련(Retraining)이나 수동 재구성(Manual Reconfiguration) 없이 학습된 능력을 새로운 조건으로 전이(Transfer)하는 것을 요구한다.

물리적 환경(Physical Environment)은 기하학(Geometry), 재료(Material), 날씨(Weather), 조명(Illumination), 동적 상호작용(Dynamic Interaction)에 걸쳐 매우 큰 다양성(Variability)을 나타낸다. 겉보기에 유사한 장소라도 마찰(Friction), 표면 순응성(Surface Compliance), 객체 배치(Object Placement), 센서 가시성(Sensor Visibility)이 다를 수 있다. 이러한 변화는 인식(Perception), 계획(Planning), 제어(Control)에 동시에 영향을 미친다. 일반화 가능한 피지컬 인공지능 시스템은 성공적인 행동에 중요한 환경 속성과 안전하게 무시할 수 있는 차이를 구분해야 한다.

분포 이동(Distribution Shift)은 실제 운영 조건이 모델 훈련(Model Training)에 사용된 데이터와 달라질 때 발생한다. 이러한 변화에는 센서 특성(Sensor Characteristic), 객체 범주(Object Category), 로봇 구성(Robot Configuration), 상호작용 동역학(Interaction Dynamics)이 포함될 수 있다. 기존 머신러닝(Machine Learning) 시스템은 훈련 분포(Training Distribution)와 배포 분포(Deployment Distribution)가 충분히 유사하다고 가정하는 경우가 많다. 반면 피지컬 인공지능은 익숙하지 않은 조건을 감지하고 이러한 가정이 더 이상 성립하지 않을 때 행동을 적응시켜야 한다.

시각적 외형(Visual Appearance)에 대한 일반화는 필요하지만 물리적 능력(Physical Competence)을 확보하기에는 충분하지 않다. 로봇은 서로 다른 조명 조건에서 객체를 인식할 수 있어도 질량(Mass), 마찰(Friction), 강성(Stiffness)이 익숙한 사례와 다르면 조작에 실패할 수 있다. 물리적 일반화(Physical Generalization)는 관측 가능한 특성(Observable Characteristic)과 숨겨진 기계적 특성(Hidden Mechanical Property) 사이의 관계를 이해해야 한다. 이러한 이해는 촉각 피드백(Tactile Feedback)과 능동적 상호작용(Active Interaction)에 의존하는 경우가 많다.

기하학적 일반화(Geometric Generalization)는 익숙하지 않은 형상(Shape), 치수(Dimension), 공간 배치(Spatial Arrangement), 장애물(Obstacle)에 걸쳐 작동하는 능력을 의미한다. 조작 정책(Manipulation Policy)은 서로 다른 크기와 파지 표면(Grasping Surface)을 가진 객체에 적응해야 하며, 내비게이션 시스템(Navigation System)은 변화하는 통로(Corridor), 경사(Slope), 여유 공간(Clearance)을 처리해야 한다. 기하학적 관계(Geometric Relationship)와 기능적 제약(Functional Constraint)에 기반한 표현은 암기된 구성(Memorized Configuration)에 의존하는 정책보다 효과적으로 전이될 수 있다.

동역학적 일반화(Dynamic Generalization)는 물리적 상호작용이 훈련 경험과 달라질 때 중요해진다. 접촉력(Contact Force), 액추에이터 응답(Actuator Response), 탑재 하중 변화(Payload Variation), 환경 교란(Environmental Disturbance)은 시스템의 행동을 변화시킬 수 있다. 특정 표면에서 훈련된 제어기(Controller)는 마찰 특성이 다른 표면에서 불안정해질 수 있다. 강건한 시스템(Robust System)은 안정성(Stability)과 안전 제약(Safety Constraint)을 준수하면서 변화하는 동역학을 추정하고 제어 전략(Control Strategy)을 조정해야 한다.

작업 일반화(Task Generalization)는 로봇이 기존 기술(Skill)을 익숙하지 않은 목표(Objective)와 행동 조합(Action Combination)에 적용하는 능력을 요구한다. 객체를 파지(Grasping), 운반(Transporting), 배치(Placing)할 수 있는 로봇은 이상적으로 모든 시퀀스에 대한 시연(Demonstration)을 수집하지 않고도 이러한 능력을 새로운 작업 흐름(Workflow)으로 결합할 수 있어야 한다. 계층적 정책(Hierarchical Policy)과 재사용 가능한 기술(Reusable Skill)은 이러한 조합을 지원할 수 있지만, 의존 관계(Dependency)를 조정하고 예상하지 못한 실패에서 복구하는 일은 여전히 어렵다.

조합적 일반화(Compositional Generalization)는 이전에 학습한 개념(Concept)을 새로운 구성으로 결합함으로써 이러한 개념을 확장한다. 로봇은 문(Door), 용기(Container), 도구(Tool), 장애물(Obstacle)을 개별적으로 이해하더라도 익숙하지 않은 작업에서 이들을 함께 마주할 수 있다. 성공적인 행동을 위해서는 이들 사이의 관계와 상호작용의 결과를 추론해야 한다. 이러한 능력은 특정 훈련 사례를 넘어 기능적 의미(Functional Meaning)를 보존하는 구조화된 표현(Structured Representation)에 의존한다.

시뮬레이션(Simulation)은 실제 배포(Physical Deployment) 전에 로봇을 다양한 조건에 노출시키는 확장 가능한 방법을 제공한다. 도메인 무작위화(Domain Randomization)는 조명, 질감(Texture), 기하학, 마찰, 질량, 액추에이터 매개변수(Actuator Parameter)를 변화시켜 훈련 범위(Training Coverage)를 확대할 수 있다. 그러나 과도한 무작위화는 비현실적인 경험(Unrealistic Experience)을 생성할 수 있으며, 불충분한 변화는 중요한 공백을 남긴다. 효과적인 시뮬레이션은 다양성(Diversity), 물리적 타당성(Physical Plausibility), 실제 배포 조건과의 관련성(Relevance) 사이에서 균형을 유지해야 한다.

시뮬레이션에서 현실 세계로의 전이(Sim-to-Real Transfer)는 시뮬레이션 환경이 물리적 상호작용의 모든 세부 사항을 재현할 수 없기 때문에 여전히 어렵다. 센서 잡음(Sensor Noise), 접촉 역학(Contact Mechanics), 재료 변형(Material Deformation), 하드웨어 불완전성(Hardware Imperfection)은 시뮬레이션과 실제 행동 사이에 차이(Discrepancy)를 발생시킨다. 따라서 일반화는 어떤 시뮬레이션 오차(Simulation Error)가 작업 성공(Task Success)에 영향을 미치는지 식별하고, 실제 배포 과정에서 이러한 차이를 허용하거나 보상할 수 있는 정책을 개발하는 데 의존한다.

월드 모델(World Model)은 특정 관측(Observation)을 암기하는 대신 물리적 관계(Physical Relationship)를 표현함으로써 일반화를 향상시킬 수 있다. 객체 동역학(Object Dynamics), 접촉 조건(Contact Condition), 인과적 의존성(Causal Dependency)을 포착하는 예측 모델(Predictive Model)은 익숙하지 않은 환경에서 계획을 지원할 가능성이 있다. 그러나 학습된 월드 모델 역시 분포 이동(Distribution Shift) 상황에서 실패할 수 있다. 따라서 예측에는 불확실성 추정(Uncertainty Estimation)과 부정확한 가정(Inaccurate Assumption)을 수정하는 메커니즘이 수반되어야 한다.

인과적 추론(Causal Reasoning)은 전이 가능한 물리 지능(Transferable Physical Intelligence)을 위한 또 다른 유망한 기반을 제공한다. 통계적 상관관계(Statistical Correlation)는 환경에 따라 달라질 수 있지만, 일부 근본적인 물리 메커니즘(Physical Mechanism)은 비교적 안정적으로 유지된다. 마찰이 미끄러짐에 어떤 영향을 미치는지 이해하는 로봇은 움직임을 표면 외형(Surface Appearance)과만 연관시키는 로봇보다 효과적으로 적응할 수 있다. 따라서 불변의 인과관계(Invariant Causal Relationship)를 식별하는 것은 중요한 연구 방향이다.

소수 사례 적응(Few-Shot Adaptation)은 로봇이 새로운 조건을 마주했지만 추가 경험(Additional Experience)을 소량만 확보할 수 있는 상황을 다룬다. 시스템은 전체 모델을 재훈련하는 대신 선택된 매개변수(Selected Parameter)를 갱신하거나, 관련 기억(Relevant Memory)을 검색하거나, 제한된 상호작용을 통해 익숙하지 않은 물리적 특성을 추정할 수 있다. 핵심 과제는 이전에 신뢰성 있게 수행하던 행동을 불안정하게 만들거나 운영 안전 요구사항(Operational Safety Requirement)을 위반하지 않으면서 빠르게 적응하는 것이다.

메타학습(Meta-Learning)은 다양한 경험에 걸쳐 훈련함으로써 새로운 작업을 학습하는 능력을 향상시키는 것을 목표로 한다. 여러 조작 또는 내비게이션 조건에 노출된 로봇은 익숙하지 않은 상황으로 전이할 수 있는 적응 전략(Adaptation Strategy)을 습득할 수 있다. 그러나 메타학습의 성능은 훈련 작업(Training Task)의 다양성과 구조에 크게 의존한다. 연구에서는 학습된 적응 메커니즘(Learned Adaptation Mechanism)이 진정으로 새로운 물리적 조건에서도 효과적으로 유지되는지를 규명해야 한다.

지속 학습(Continual Learning)은 로봇이 배포 기간 전체에 걸쳐 지식을 축적할 수 있도록 하는 장기적인 일반화 접근법을 제공한다. 새로운 환경, 객체, 운영 조건(Operating Condition)은 고립된 예외가 아니라 개선을 위한 기회가 된다. 그러나 지속적인 갱신(Continual Update)은 파국적 망각(Catastrophic Forgetting)과 성능 퇴행(Performance Regression)의 위험을 초래한다. 신뢰할 수 있는 시스템은 갱신된 정책(Updated Policy)을 광범위하게 배포하기 전에 기억 관리(Memory Management), 통제된 적응(Controlled Adaptation), 검증(Validation)을 수행해야 한다.

신체 구조 간 일반화(Cross-Embodiment Generalization)는 로봇마다 형태(Morphology), 센싱(Sensing), 구동(Actuation), 물리적 제약(Physical Constraint)이 다르기 때문에 추가적인 복잡성을 발생시킨다. 객체 정체성(Object Identity)과 환경 기하학(Environmental Geometry)에 관한 지식은 플랫폼 사이에서 전이될 수 있지만, 이동(Locomotion)과 조작 전략은 적응이 필요한 경우가 많다. 공유 표현(Shared Representation)은 신체 구조에 독립적인 물리적 지식(Embodiment-Independent Physical Knowledge)과 각 로봇의 기계적 구성(Mechanical Configuration)에 의해 결정되는 능력을 분리해야 한다.

언어 조건부 정책(Language-Conditioned Policy)은 인간의 명령(Human Instruction)을 재사용 가능한 물리적 기술과 연결함으로써 일반화를 지원할 수 있다. 자연어(Natural Language)는 작업별 프로그래밍(Task-Specific Programming) 없이 새로운 목표를 설명할 수 있지만, 언어적 이해(Linguistic Understanding)가 실행 가능한 행동(Executable Behavior)을 보장하지는 않는다. 로봇은 명령을 현재 관측(Current Observation), 사용 가능한 행동(Available Action), 물리적 제약, 작업 실현 가능성(Task Feasibility)에 연결해야 한다. 신뢰할 수 있는 실행에는 환경으로부터의 지속적인 피드백(Continuous Feedback)이 필요하다.

불확실성 인식(Uncertainty Awareness)은 시스템이 익숙하지 않은 상황을 마주하면서 자신의 한계를 인식하지 못할 때 일반화 실패(Generalization Failure)가 자주 발생하므로 필수적이다. 로봇은 현재 관측과 동역학이 신뢰할 수 있는 운영 범위(Reliable Operating Range)에 포함되는지 추정해야 한다. 신뢰도(Confidence)가 낮아지면 근거가 부족한 예측을 계속 수행하는 대신 속도를 줄이거나, 추가 정보를 수집하거나, 지원을 요청하거나, 보수적 제어 전략(Conservative Control Strategy)을 활성화할 수 있다.

안전 제약(Safety Constraint)은 학습된 정책의 일반화 성능이 저하되더라도 효과적으로 유지되어야 한다. 충돌 회피(Collision Avoidance), 힘 제한(Force Limit), 안정성 모니터링(Stability Monitoring), 비상 정지(Emergency Stopping)는 범용 신경망 모델(General-Purpose Neural Model)의 정확도에 전적으로 의존해서는 안 된다. 하이브리드 아키텍처(Hybrid Architecture)는 적응형 학습(Adaptive Learning)과 검증된 보호 메커니즘(Verified Protective Mechanism)을 결합할 수 있다. 이러한 분리는 명확하게 정의된 운영 경계(Operational Boundary)를 유지하면서 익숙하지 않은 조건을 탐색할 수 있도록 한다.

실제 세계 일반화의 평가(Evaluation)는 훈련 조건과 의미 있게 다른 환경에서의 시험을 필요로 한다. 유사한 시연을 훈련 데이터셋(Training Dataset)과 테스트 데이터셋(Test Dataset)으로 무작위 분할하면 전이 능력(Transfer Capability)을 과대평가할 수 있다. 보다 유익한 벤치마크(Benchmark)는 평가 경험과 훈련 경험 사이의 숨겨진 중복(Hidden Overlap)을 방지하면서 객체 범주, 물리적 특성, 배치(Layout), 작업, 하드웨어 구성(Hardware Configuration), 환경 동역학(Environmental Dynamics)을 변화시켜야 한다.

일반화는 개별적인 성공 시험(Isolated Successful Trial)이 아니라 장기간의 운영(Extended Operation)에 걸쳐 평가되어야 한다. 정책은 초기에는 우수한 성능을 보이더라도 센서 드리프트(Sensor Drift), 표면 마모(Surface Wear), 탑재 하중 변화(Payload Change), 환경 조건의 변화로 인해 성능이 저하될 수 있다. 장기 평가(Long-Term Evaluation)는 신뢰성(Reliability), 복구 행동(Recovery Behavior), 적응 효율성(Adaptation Efficiency), 안전 사고(Safety Incident), 성능 유지에 필요한 계산 비용(Computational Cost)과 데이터 비용(Data Cost)을 검토해야 한다.

중요한 연구 질문은 범용 모델(Universal Model)과 전문화된 적응(Specialized Adaptation) 사이의 균형에 관한 것이다. 대규모 파운데이션 모델(Large Foundation Model)은 폭넓게 전이 가능한 표현(Transferable Representation)을 제공할 수 있는 반면, 더 작은 작업 특화 제어기(Task-Specific Controller)는 정밀하고 효율적인 물리적 실행(Physical Execution)을 제공할 수 있다. 계층적 아키텍처(Hierarchical Architecture)는 범용 추론(General Reasoning)을 국소 동역학 추정(Local Dynamics Estimation) 및 전문화된 제어(Specialized Control)와 결합할 수 있다. 이러한 구성 요소가 어떻게 상호작용해야 하는지는 여전히 해결되지 않은 과제이다.

궁극적으로 실제 세계 일반화(Real-World Generalization)는 단순히 익숙하지 않은 장면을 인식하거나 새로운 장소에서 이전에 학습한 행동을 실행하는 능력이 아니다. 이를 위해서는 전이 가능한 물리적 지식(Transferable Physical Knowledge), 인과적 이해(Causal Understanding), 적응형 제어(Adaptive Control), 불확실성 추정(Uncertainty Estimation), 지속 학습(Continual Learning), 신뢰할 수 있는 안전 메커니즘(Reliable Safety Mechanism)이 필요하다. 발전 수준은 피지컬 인공지능 시스템이 최소한의 추가 감독(Additional Supervision)과 경험만으로 진정으로 익숙하지 않은 조건에서도 얼마나 효과적으로 능력(Competence)을 유지하는지에 따라 평가될 것이다.

## 07.06. Cross Embodiment Transfer

![](images/image6.png){width="7.268055555555556in" height="7.268055555555556in"}

신체 구조 간 전이(Cross-Embodiment Transfer)는 서로 다른 신체를 가진 로봇이 기계적 구조(Mechanical Structure), 센싱(Sensing), 구동(Actuation)의 차이에도 불구하고 지식을 공유하는 방법을 학습해야 하므로 피지컬 인공지능(Physical AI)의 근본적인 과제이다. 한 로봇이 학습한 조작 전략(Manipulation Strategy)은 관절(Joint)이나 그리퍼(Gripper)가 다른 로봇에 직접 적용되지 않을 수 있다. 성공적인 전이를 위해서는 일반적인 물리적 지식(General Physical Knowledge)을 신체 구조별 능력(Embodiment-Specific Capability) 및 제약(Constraint)과 분리해야 한다.

신체 구조(Embodiment)는 지능형 시스템(Intelligent System)이 환경을 인식하고 상호작용하는 방식을 결정한다. 휴머노이드(Humanoid), 모바일 매니퓰레이터(Mobile Manipulator), 사족보행 로봇(Quadruped), 산업용 로봇 팔(Industrial Arm)은 서로 다른 운동학적 구조(Kinematic Structure), 작업 공간(Workspace), 제어 인터페이스(Control Interface)를 가진다. 이들은 공통된 물리 법칙(Physical Law)에 따라 작동하지만 수행할 수 있는 행동은 상당히 다르다. 신체 구조 간 학습(Cross-Embodiment Learning)은 이러한 차이에도 불구하고 경험의 어떤 측면이 전이 가능한지 식별해야 한다.

핵심적인 어려움은 행동 공간(Action Space) 사이의 불일치(Mismatch)에 있다. 어떤 로봇은 관절 토크(Joint Torque)를 제어하고, 다른 로봇은 말단 효과기 위치(End-Effector Position)를 명령하며, 또 다른 로봇은 속도 기반 인터페이스(Velocity-Based Interface)를 사용할 수 있다. 이러한 시스템 사이에서 저수준 정책(Low-Level Policy)을 직접 전이하면 유효하지 않거나 위험한 행동이 발생할 수 있다. 공유 행동 표현(Shared Action Representation)은 기능적 의도(Functional Intention)를 표현하면서 각 신체 구조가 이를 실행 가능한 모터 명령(Motor Command)으로 변환할 수 있도록 해야 한다.

작업 공간 표현(Task-Space Representation)은 조작 기술(Manipulation Skill)을 전이하기 위한 하나의 접근법을 제공한다. 정책(Policy)은 개별 관절 움직임을 통해 행동을 설명하는 대신 원하는 객체 움직임(Object Motion), 말단 효과기 궤적(End-Effector Trajectory), 접촉 관계(Contact Relationship)를 지정할 수 있다. 이후 신체 구조별 제어기(Embodiment-Specific Controller)가 적절한 관절 명령(Joint Command)을 생성한다. 이러한 분리는 이식성(Portability)을 향상시킬 수 있지만, 도달 가능성(Reachability), 조작 능력(Dexterity), 힘 용량(Force Capacity)의 차이는 여전히 전이를 제한한다.

객체 중심 표현(Object-Centered Representation)은 공유 물리 지능(Shared Physical Intelligence)을 위한 또 다른 기반을 제공한다. 로봇은 자신의 형태(Morphology)에 의존하지 않고 객체의 기하학(Geometry), 자세(Pose), 재료 특성(Material Property), 기능적 어포던스(Functional Affordance)를 통해 객체를 설명할 수 있다. 이러한 표현은 파지(Grasping), 밀기(Pushing), 들어 올리기(Lifting), 배치(Placement)에 관한 공통 추론(Common Reasoning)을 지원한다. 그러나 특정 행동의 실행 가능성(Feasibility)은 객체 특성과 로봇 능력 사이의 상호작용에 따라 결정된다.

어포던스 학습(Affordance Learning)은 환경이 제공하는 행동 가능성(Environmental Opportunity)을 신체 구조별 능력과 연결한다. 손잡이(Handle)는 적절한 그리퍼를 가진 로봇에는 당기기 어포던스(Pulling Affordance)를 제공할 수 있지만, 조작 하드웨어(Manipulation Hardware)가 없는 플랫폼에는 접근할 수 없는 대상일 수 있다. 따라서 어포던스를 항상 객체 자체의 고유한 특성(Intrinsic Object Property)으로 취급할 수는 없다. 전이 가능한 모델(Transferable Model)은 객체, 의도된 행동(Intended Action), 환경 조건(Environmental Condition), 사용 가능한 로봇 능력 사이의 관계를 표현해야 한다.

형태학적 다양성(Morphological Diversity)은 이동 능력 전이(Locomotion Transfer)에 상당한 어려움을 발생시킨다. 바퀴형 로봇(Wheeled Robot), 사족보행 로봇(Quadruped), 휴머노이드(Humanoid), 궤도형 플랫폼(Tracked Platform)은 서로 다른 접촉 메커니즘(Contact Mechanism)을 통해 지형(Terrain)을 극복한다. 내비게이션 목표(Navigation Objective)는 공유할 수 있지만, 이동 전략(Movement Strategy)은 안정성(Stability), 견인력(Traction), 여유 공간(Clearance), 액추에이터 한계(Actuator Limit)를 반영해야 한다. 신체 구조 간 전이는 상위 수준의 내비게이션 지식(High-Level Navigation Knowledge)을 보존하면서 각 플랫폼에 맞게 이동 제어(Locomotion Control)를 적응시켜야 한다.

공유 잠재 공간(Shared Latent Space)은 서로 다른 로봇 구성(Robotic Configuration)에 걸쳐 정책이 작동하도록 지원할 수 있다. 인코더(Encoder)는 이질적인 센서 관측(Heterogeneous Sensor Observation)과 고유수용감각 상태(Proprioceptive State)를 공통 표현(Common Representation)으로 변환하고, 디코더(Decoder)는 공유 명령(Shared Command)을 신체 구조별 행동(Embodiment-Specific Action)으로 변환한다. 핵심 과제는 이러한 잠재 표현(Latent Representation)이 로봇 동역학(Robot Dynamics)의 중요한 차이를 감추지 않으면서 작업 관련 물리 정보(Task-Relevant Physical Information)를 유지하도록 하는 것이다.

시각-언어-행동 모델(Vision-Language-Action Model)은 여러 로봇 유형에 걸친 학습을 위한 잠재적인 프레임워크(Framework)를 제공한다. 언어(Language)는 공통 목표(Common Goal)를 표현하고, 시각 관측(Visual Observation)은 환경적 맥락(Environmental Context)을 설명하며, 행동 모듈(Action Module)은 플랫폼별 실행(Platform-Specific Execution)을 처리할 수 있다. 다양한 로봇 데이터셋(Robotic Dataset)을 활용한 훈련은 전이 가능한 표현(Transferable Representation)을 향상시킬 수 있다. 그러나 일관되지 않은 행동 규약(Action Convention), 센서 보정(Sensor Calibration), 데이터 품질(Data Quality)은 효과적인 지식 공유(Knowledge Sharing)를 제한할 수 있다.

로봇 데이터셋(Robot Dataset)은 하드웨어 플랫폼(Hardware Platform), 연구실(Laboratory), 응용 분야(Application Domain)에 따라 분산되어 있는 경우가 많다. 서로 다른 로봇은 관절 상태(Joint State), 힘 측정값(Force Measurement), 카메라 스트림(Camera Stream), 행동 명령(Action Command)을 호환되지 않는 형식(Incompatible Format)으로 기록한다. 전이 가능한 모델을 구축하려면 형태(Morphology), 좌표계(Coordinate Frame), 액추에이터 한계, 센서 특성(Sensor Characteristic)을 설명하는 표준화된 메타데이터(Standardized Metadata)가 필요하다. 이러한 설명이 없으면 데이터셋 결합은 유용한 다양성보다 모호성(Ambiguity)을 증가시킬 수 있다.

운동학적 대응 관계(Kinematic Correspondence)는 관절 구조(Joint Structure)가 다른 로봇 사이에서 움직임 패턴(Movement Pattern)을 전이할 때 중요하다. 두 매니퓰레이터(Manipulator)는 서로 다른 관절 구성(Joint Configuration)을 통해 동일한 말단 효과기 자세(End-Effector Pose)를 달성할 수 있지만, 특정 목표 자세(Target Pose)는 한 플랫폼에서 도달할 수 없을 수도 있다. 전이 방법(Transfer Method)은 관절 한계(Joint Limit), 특이점(Singularity), 충돌 제약(Collision Constraint), 작업 공간 차이(Workspace Difference)를 고려해야 한다. 기능적 동등성(Functional Equivalence)이 동일한 모터 행동(Motor Behavior)을 의미하지는 않는다.

동역학적 대응 관계(Dynamic Correspondence)는 유사한 움직임에도 서로 다른 힘과 제어 응답(Control Response)이 필요할 수 있기 때문에 더욱 어렵다. 로봇은 질량 분포(Mass Distribution), 액추에이터 대역폭(Actuator Bandwidth), 관절 마찰(Joint Friction), 구조적 순응성(Structural Compliance), 탑재 하중 용량(Payload Capacity)이 서로 다르다. 전이된 정책(Transferred Policy)은 불안정성(Instability)이나 장비 손상(Equipment Damage)을 방지하기 위해 이러한 차이를 준수해야 한다. 동역학 인식 적응(Dynamics-Aware Adaptation)은 학습된 행동을 로봇별 모델(Robot-Specific Model) 및 온라인 매개변수 추정(Online Parameter Estimation)과 결합할 수 있다.

신체 구조 간 모방 학습(Cross-Embodiment Imitation Learning)은 시연(Demonstration)이 인간이나 서로 다른 형태의 로봇에서 제공될 때 추가적인 복잡성을 발생시킨다. 인간 손의 움직임(Human Hand Movement)은 두 손가락 그리퍼(Two-Finger Gripper)에 직접 복사할 수 없으며, 휴머노이드 보행 시연(Humanoid Locomotion Demonstration)을 사족보행 로봇에 변경 없이 적용할 수도 없다. 리타기팅 방법(Retargeting Method)은 작업 목표(Task Objective)와 관련 접촉 관계(Relevant Contact Relationship)를 보존하면서 대상 신체 구조(Target Embodiment)에 적합한 행동을 생성해야 한다.

계층적 기술 표현(Hierarchical Skill Representation)은 작업 목표와 실행 세부 사항(Execution Detail)을 분리함으로써 전이를 향상시킬 수 있다. 문 열기(Opening a Door), 객체 운반(Transporting an Object), 장비 검사(Inspecting Equipment)와 같은 상위 수준 기술(High-Level Skill)은 여러 플랫폼에서 공유될 수 있다. 저수준 제어기(Lower-Level Controller)는 사용 가능한 센서와 액추에이터에 따라 이러한 기술을 구현한다. 이러한 아키텍처는 재사용(Reuse)을 지원하지만, 신뢰할 수 있는 기술 선택(Skill Selection)을 위해서는 각 로봇의 능력을 정확하게 추정해야 한다.

월드 모델(World Model)은 특정 로봇과 독립적으로 물리적 환경이 행동에 어떻게 반응하는지를 표현함으로써 신체 구조 간 전이를 지원할 수 있다. 중력(Gravity), 객체 안정성(Object Stability), 마찰(Friction), 접촉 결과(Contact Consequence)에 관한 공유 지식(Shared Knowledge)은 여러 플랫폼에 도움이 될 수 있다. 그러나 예측에는 신체 구조에 따라 달라지는 힘(Embodiment-Dependent Force)과 도달 가능한 상호작용(Reachable Interaction)이 반영되어야 한다. 유용한 아키텍처는 일반적인 환경 동역학(General Environmental Dynamics)을 로봇별 행동 모델(Robot-Specific Action Model)과 결합한다.

인과적 표현(Causal Representation)은 순수한 통계적 연관성(Statistical Association)보다 강력한 전이를 제공할 수 있다. 지지(Support), 충돌(Collision), 객체 변위(Object Displacement)와 같은 물리적 관계는 서로 다른 로봇 신체에서도 의미를 유지한다. 밀기(Pushing)의 인과적 효과(Causal Effect)를 이해하는 로봇은 서로 다른 액추에이터를 통해 이러한 지식을 적용할 수 있다. 그러나 인과적 지식을 전이하려면 신체 구조의 변화가 행동과 결과를 연결하는 메커니즘(Mechanism)을 언제 변경하는지 인식해야 한다.

소수 사례 적응(Few-Shot Adaptation)은 학습된 능력을 전이하는 데 필요한 대상 로봇 데이터(Target-Robot Data)의 양을 줄일 수 있다. 사전 훈련된 정책(Pretrained Policy)은 제한된 수의 시연이나 상호작용을 사용하여 행동 매핑(Action Mapping)을 보정하고 익숙하지 않은 동역학(Unfamiliar Dynamics)을 추정할 수 있다. 매개변수 효율적 적응(Parameter-Efficient Adaptation)과 모듈형 정책 아키텍처(Modular Policy Architecture)는 유망한 접근법이다. 특히 대상 하드웨어(Target Hardware)가 크게 다를 경우 물리적 제약 아래에서 이러한 방법의 신뢰성을 평가해야 한다.

시뮬레이션(Simulation)은 신체 구조 간 전이를 훈련하고 평가하기 위한 통제된 환경(Controlled Environment)을 제공한다. 여러 로봇 형태(Robot Morphology)가 비교 가능한 환경 조건(Comparable Environmental Condition)에서 관련 작업을 수행하도록 하여 연구자가 기계적 차이(Mechanical Difference)의 영향을 분리할 수 있다. 시뮬레이션은 관절 구조, 액추에이터 특성(Actuator Characteristic), 탑재 하중(Payload)의 체계적인 변화도 지원한다. 그러나 시뮬레이션에서 성공적인 전이가 실제 하드웨어(Real Hardware)에서 신뢰할 수 있는 행동을 보장하지는 않는다.

안전성(Safety)은 전이된 정책이 원본 로봇(Source Robot)에는 없었던 물리적 제약을 마주할 수 있기 때문에 특히 중요하다. 강력한 산업용 매니퓰레이터(Industrial Manipulator)에서 실행 가능한 명령은 경량 협동로봇(Lightweight Collaborative Robot)의 힘 한계(Force Limit)를 초과할 수 있다. 마찬가지로 이동 전략(Locomotion Strategy)이 다른 플랫폼의 안정성 제약(Stability Constraint)을 위반할 수도 있다. 전이 시스템(Transfer System)은 실행 전에 신체 구조별 안전 범위(Embodiment-Specific Safety Envelope)에 따라 행동을 검증해야 한다.

평가(Evaluation)는 인식(Perception), 계획(Planning), 조작(Manipulation), 이동(Locomotion), 전체 작업 실행(Complete Task Execution)의 전이를 구분해야 한다. 공유된 시각 인식 작업(Visual Recognition Task)에서 성공했다고 해서 전이 가능한 운동 지능(Transferable Motor Intelligence)이 입증되는 것은 아니다. 벤치마크(Benchmark)는 형태가 의미 있게 다른 로봇을 포함하고, 대상 작업 성공률(Target-Task Success), 적응 데이터 요구량(Adaptation Data Requirement), 안전성, 성능 저하(Performance Degradation)를 측정해야 한다. 또한 시험 과정에서는 원본 경험(Source Experience)과 대상 경험(Target Experience) 사이의 숨겨진 중복(Hidden Overlap)을 방지해야 한다.

중요한 미해결 질문은 물리 지능(Physical Intelligence)의 어느 정도가 진정으로 신체 구조에 독립적(Embodiment-Independent)일 수 있는지에 관한 것이다. 기하학적 추론(Geometric Reasoning), 객체 영속성(Object Permanence), 일부 인과적 원리(Causal Principle)는 광범위하게 전이될 수 있지만, 정밀 제어(Precise Control)와 접촉 행동(Contact Behavior)은 신체에 크게 의존한다. 공유 지식(Shared Knowledge)과 전문화된 능력(Specialized Competence) 사이의 경계는 고정되어 있지 않을 가능성이 높다. 이는 작업 복잡도(Task Complexity), 센서 가용성(Sensor Availability), 요구되는 물리적 정밀도(Physical Precision)에 따라 달라질 수 있다.

대규모 다중 로봇 학습(Large-Scale Multi-Robot Learning)은 추가적인 신체 구조가 경험을 제공할수록 개선되는 공유 표현(Shared Representation)을 생성할 수 있다. 서로 다른 로봇 플랫폼으로 구성된 플릿(Fleet)은 환경 구조(Environmental Structure), 작업 전략(Task Strategy), 실패 패턴(Failure Pattern)을 공동으로 학습할 수 있다. 그러나 유용한 경험 통합(Experience Aggregation)을 위해서는 이질적인 데이터(Heterogeneous Data)와 하드웨어 한계(Hardware Limitation)를 신중하게 처리해야 한다. 공유 학습(Shared Learning)은 보편적으로 적용 가능한 지식(Universally Applicable Knowledge)과 플랫폼별 행동(Platform-Specific Behavior) 사이의 차이를 보존해야 한다.

궁극적으로 신체 구조 간 전이(Cross-Embodiment Transfer)는 단순히 서로 다른 로봇 사이에서 신경망 매개변수(Neural Network Parameter)를 재사용하는 문제가 아니다. 이를 위해서는 공통 물리적 표현(Common Physical Representation), 기능적 행동 추상화(Functional Action Abstraction), 형태 인식 적응(Morphology-Aware Adaptation), 인과적 이해(Causal Understanding), 신뢰할 수 있는 신체 구조별 제어(Reliable Embodiment-Specific Control)가 필요하다. 이러한 과제를 해결하면 피지컬 인공지능 시스템은 다양한 로봇 플랫폼에 걸쳐 지식을 축적하고 점차 더 범용적인 물리 지능(General Physical Intelligence)으로 발전할 수 있을 것이다.

## 07.07. Learning from Limited Real World Data

![](images/image7.png){width="7.268055555555556in" height="7.268055555555556in"}

제한된 실제 세계 데이터로부터의 학습(Learning from Limited Real-World Data)은 물리적 상호작용 경험(Physical Interaction Experience)을 수집하는 데 높은 비용과 많은 시간이 필요하고 잠재적인 위험까지 수반되므로 피지컬 인공지능(Physical AI)의 핵심 과제이다. 디지털 학습 시스템(Digital Learning System)과 달리 로봇은 현실에 기반한 지식(Grounded Knowledge)을 획득하기 위해 실제 객체, 환경, 하드웨어와 상호작용해야 한다. 데이터 효율적 학습(Data-Efficient Learning)은 비교적 적은 양의 물리적 경험으로 신뢰할 수 있는 인식(Perception), 계획(Planning), 제어(Control) 능력을 개발하는 것을 목표로 한다.

실제 로봇 데이터(Real-World Robotic Data)는 장비 비용(Equipment Cost), 운영 시간(Operational Time), 인간 감독(Human Supervision), 안전 요구사항(Safety Requirement)에 의해 제약받는다. 각 시연(Demonstration)에는 환경 준비(Environment Preparation), 센서 보정(Sensor Calibration), 작업 실행(Task Execution), 실패 복구(Failure Recovery)가 필요할 수 있다. 하드웨어 마모(Hardware Wear)와 유지보수(Maintenance)는 데이터 수집 능력(Collection Capacity)을 더욱 제한한다. 이러한 제약으로 인해 기존의 대규모 데이터 수집 전략(Large-Scale Data Collection Strategy)을 체화 지능(Embodied Intelligence)에 직접 적용하기 어렵다.

데이터 부족(Data Scarcity)은 희귀 사건(Rare Event)과 복잡한 물리적 상호작용(Complex Physical Interaction)에서 특히 심각해진다. 로봇 고장(Robot Failure), 예상하지 못한 충돌(Unexpected Collision), 특이한 재료 거동(Unusual Material Behavior), 위험한 환경 조건(Hazardous Environmental Condition)은 드물게 발생하지만 신뢰할 수 있는 자율성(Reliable Autonomy)을 확보하는 데 매우 중요하다. 대부분 성공적인 일상 작업으로 구성된 데이터셋(Dataset)은 이러한 상황을 충분히 표현하지 못할 수 있다. 따라서 학습 시스템은 희소하고 불균등하게 분포된 경험(Sparse and Unevenly Distributed Experience)에서 의미 있는 지식을 추출해야 한다.

샘플 효율성(Sample Efficiency)은 제한된 상호작용 데이터(Interaction Data)를 사용하여 학습 알고리즘(Learning Algorithm)이 성능을 얼마나 효과적으로 향상시키는지를 측정한다. 샘플 효율적인 로봇(Sample-Efficient Robot)은 수천 번의 반복적인 물리 실험(Physical Trial) 없이도 유용한 기술(Skill)을 습득해야 한다. 이를 달성하려면 사전 지식(Prior Knowledge), 구조화된 표현(Structured Representation), 예측 모델(Predictive Model)을 활용해야 한다. 그러나 효율성은 안전성(Safety), 강건성(Robustness), 수집된 사례를 넘어 일반화(Generalization)하는 능력과 함께 평가되어야 한다.

전이 학습(Transfer Learning)은 실제 세계 데이터 요구량(Real-World Data Requirement)을 줄이기 위한 실용적인 접근법을 제공한다. 관련 작업(Related Task), 시뮬레이션 환경(Simulated Environment), 다양한 로봇 데이터셋(Robotic Dataset)으로 사전 훈련된 모델(Pretrained Model)은 재사용 가능한 표현(Reusable Representation)과 초기 제어 전략(Initial Control Strategy)을 제공할 수 있다. 이후 미세조정(Fine-Tuning)을 통해 이러한 능력을 대상 로봇(Target Robot)과 환경에 적응시킨다. 전이의 효과는 물리 동역학(Physical Dynamics), 센싱 조건(Sensing Condition), 작업 요구사항(Task Requirement)의 유사성에 따라 달라진다.

파운데이션 모델(Foundation Model)은 대규모 이미지(Image), 영상(Video), 언어(Language) 데이터셋에서 획득한 폭넓은 인식적·의미적 지식(Perceptual and Semantic Knowledge)을 제공할 수 있다. 이러한 지식은 제한된 로봇별 훈련(Robot-Specific Training)만으로 객체 인식(Object Recognition), 작업 해석(Task Interpretation), 상위 수준 계획(High-Level Planning)을 향상시킬 수 있다. 그러나 시각 및 언어 사전 훈련(Visual and Linguistic Pretraining)이 물리적 경험을 완전히 대체할 수는 없다. 접촉 동역학(Contact Dynamics), 힘 제어(Force Control), 액추에이터 거동(Actuator Behavior)은 여전히 현실에 기반한 적응(Grounded Adaptation)과 검증(Validation)을 필요로 한다.

시뮬레이션(Simulation)은 실제 세계 상호작용(Real-World Interaction)이 제한될 때 보완적인 경험(Supplementary Experience)을 제공하는 중요한 수단이다. 로봇은 반복적인 시뮬레이션 실험(Simulated Trial)을 통해 조작(Manipulation), 내비게이션(Navigation), 복구 행동(Recovery Behavior)을 연습할 수 있다. 합성 환경(Synthetic Environment)은 물리적 매개변수(Physical Parameter)와 작업 조건(Task Condition)의 체계적인 변화도 가능하게 한다. 그러나 시뮬레이션 오차(Simulation Error)는 잘못된 경험(Misleading Experience)을 제공할 수 있으므로 신중한 보정(Calibration)과 실제 세계 검증(Real-World Validation)이 필수적이다.

시뮬레이션에서 현실 세계로의 학습(Sim-to-Real Learning)은 풍부한 시뮬레이션 경험(Simulated Experience)과 제한된 물리적 데이터(Physical Data)를 결합하는 것을 목표로 한다. 로봇은 시뮬레이션에서 초기 정책(Preliminary Policy)을 학습한 후 소수의 실제 세계 상호작용을 통해 이를 개선할 수 있다. 도메인 무작위화(Domain Randomization), 시스템 식별(System Identification), 잔차 동역학 학습(Residual Dynamics Learning)은 환경 사이의 차이(Discrepancy)를 줄일 수 있다. 핵심 과제는 어떤 실제 세계 측정값(Real-World Measurement)이 전이 신뢰성(Transfer Reliability)을 가장 크게 향상시키는지 판단하는 것이다.

자기지도학습(Self-Supervised Learning)은 광범위한 수동 레이블(Manual Label) 없이 감각 데이터(Sensory Data)를 활용할 수 있다. 로봇은 미래 관측(Future Observation)을 예측하거나, 누락된 측정값(Missing Measurement)을 복원하거나, 행동과 결과 사이의 관계를 식별함으로써 표현을 학습할 수 있다. 카메라(Camera), 촉각 센서(Tactile Sensor), 고유수용감각 시스템(Proprioceptive System)에서 수집되는 연속적인 데이터 스트림(Continuous Data Stream)은 유용한 훈련 신호(Training Signal)를 제공한다. 그러나 학습된 표현은 물리적 의사결정(Physical Decision-Making)에 필요한 정보를 보존해야 한다.

모방 학습(Imitation Learning)은 전문가 시연(Expert Demonstration)을 활용할 수 있지만 자율 탐색(Autonomous Exploration)에 높은 비용이 발생하는 경우 특히 유용하다. 로봇은 인간이나 다른 로봇 시스템이 제공한 사례를 통해 조작 또는 내비게이션 행동을 학습할 수 있다. 행동 복제(Behavioral Cloning)는 직접적인 학습 방법을 제공하지만, 제한된 시연으로는 복구 상태(Recovery State)나 예상하지 못한 교란(Unexpected Disturbance)을 충분히 다루지 못할 수 있다. 따라서 추가적인 상호작용과 교정 피드백(Corrective Feedback)이 필요한 경우가 많다.

소수 사례 학습(Few-Shot Learning)은 적은 수의 사례로 새로운 기술(New Skill)을 습득하는 능력을 다룬다. 로봇은 몇 차례의 시연만으로 익숙하지 않은 객체를 조작하거나 새로운 작업 공간(Workspace)에 적응해야 할 수 있다. 메타학습(Meta-Learning)과 사전 훈련된 기술 표현(Pretrained Skill Representation)은 이러한 적응을 가속할 수 있다. 그러나 객체 특성(Object Property), 접촉 조건(Contact Condition), 작업 요구사항이 이전 경험과 크게 다른 경우에도 소수 사례 학습의 성능은 신뢰할 수 있어야 한다.

능동 학습(Active Learning)은 정보 가치가 높은 관측(Informative Observation)과 상호작용을 선택함으로써 데이터 효율성(Data Efficiency)을 향상시킨다. 로봇은 가능한 모든 궤적(Trajectory)을 수집하는 대신 추가 경험이 중요한 불확실성(Uncertainty)을 줄일 수 있는 상황을 식별한다. 예를 들어 마찰(Friction)을 추정하기 위해 제어된 밀기 동작(Controlled Push)을 수행하거나 안정성(Stability)을 평가하기 위해 파지(Grasp)를 시험할 수 있다. 이러한 행동은 물리적 안전 제약(Physical Safety Constraint)을 준수하면서 학습 가치(Learning Value)를 최대화해야 한다.

불확실성 인식 탐색(Uncertainty-Aware Exploration)은 데이터가 부족할 때 로봇이 학습 경험 밖의 조건을 마주할 수 있으므로 필수적이다. 베이지안 모델(Bayesian Model), 앙상블(Ensemble), 신뢰도 추정(Confidence Estimation)은 충분히 이해되지 않은 동역학(Dynamics)을 식별하는 데 도움이 될 수 있다. 이후 탐색 전략(Exploration Strategy)은 정보 가치가 높으면서도 관리 가능한 상호작용을 우선할 수 있다. 그러나 심각한 분포 이동(Distribution Shift)에서는 불확실성 추정 자체도 신뢰할 수 없게 될 수 있으므로 보수적인 안전장치(Conservative Safeguard)가 필요하다.

모델 기반 강화학습(Model-Based Reinforcement Learning)은 학습된 동역학(Learned Dynamics)을 사용하여 후보 행동(Candidate Action)의 결과를 예측함으로써 상호작용 요구량(Interaction Requirement)을 줄일 수 있다. 로봇은 모든 전략을 물리적 실험으로 평가하는 대신 내부 월드 모델(Internal World Model)에서 대안적인 행동을 시뮬레이션할 수 있다. 실제 세계 관측은 모델을 주기적으로 갱신한다. 이러한 접근법은 예측이 정확할 때 효율성을 향상시키지만, 학습된 동역학이 불완전하면 오차를 증폭시킬 수 있다.

오프라인 강화학습(Offline Reinforcement Learning)은 지속적인 물리적 탐색 없이 이전에 수집된 데이터셋으로부터 정책(Policy)을 학습하는 또 다른 접근법을 제공한다. 과거 시연(Historical Demonstration), 운영 로그(Operational Log), 기록된 실패(Recorded Failure)는 가치 있는 경험을 제공할 수 있다. 그러나 오프라인 정책(Offline Policy)은 데이터 분포(Data Distribution)와 상당히 다른 행동을 제안할 수 있다. 근거가 부족한 외삽(Unsupported Extrapolation)을 줄이기 위해서는 보수적 학습 목표(Conservative Learning Objective)와 불확실성 추정(Uncertainty Estimation)이 필요하다.

물리적 경험이 제한적일 때 데이터 품질(Data Quality)은 데이터 양(Data Volume)보다 더 중요할 수 있다. 정확한 타임스탬프(Timestamp), 보정된 센서(Calibrated Sensor), 동기화된 행동 기록(Synchronized Action Record), 신뢰할 수 있는 작업 주석(Task Annotation)은 각 궤적의 유용성을 높인다. 손상된 측정값(Corrupted Measurement)이나 일관되지 않은 좌표계(Inconsistent Coordinate Frame)는 데이터셋이 크더라도 학습을 저해할 수 있다. 신중한 데이터 큐레이션(Data Curation)은 부족한 물리적 데이터가 의미 있는 훈련 정보(Training Information)로 활용되도록 돕는다.

경험 재생(Experience Replay)과 기억 시스템(Memory System)은 로봇이 학습 과정에서 가치 있는 상호작용을 재사용할 수 있도록 한다. 드문 실패(Rare Failure), 성공적인 복구(Successful Recovery), 정보 가치가 높은 접촉 사건(Informative Contact Event)은 반복적인 일상 궤적(Routine Trajectory)보다 더 많은 주의를 기울일 가치가 있다. 우선순위 샘플링(Prioritized Sampling)은 학습 가치가 높은 경험을 강조함으로써 훈련 효율성(Training Efficiency)을 향상시킬 수 있다. 그러나 제한된 사례를 과도하게 재사용하면 과적합(Overfitting)이 발생하고 일반화(Generalization)가 저하될 수 있다.

다중 작업 학습(Multi-Task Learning)은 관련 목표(Related Objective) 사이에서 지식을 공유함으로써 데이터 효율성을 높일 수 있다. 파지(Grasping) 과정에서 획득한 경험은 배치(Placement), 조립(Assembly), 도구 조작(Tool Manipulation)에 활용될 수 있으며, 내비게이션 데이터(Navigation Data)는 장애물 회피(Obstacle Avoidance)와 위치 추정(Localization)을 지원할 수 있다. 공유 표현(Shared Representation)은 모든 능력을 독립적으로 학습할 필요성을 줄인다. 핵심 과제는 작업마다 상충하는 행동(Conflicting Behavior)이나 서로 다른 물리적 가정(Physical Assumption)이 필요할 때 간섭(Interference)을 방지하는 것이다.

로봇 간 데이터 공유(Cross-Robot Data Sharing)는 단일 플랫폼을 넘어 경험을 확장할 기회를 제공한다. 여러 로봇은 관측(Observation), 시연(Demonstration), 실패 기록(Failure Record)을 공유 학습 시스템(Shared Learning System)에 제공할 수 있다. 플릿 규모 학습(Fleet-Scale Learning)은 데이터 수집 비용(Collection Cost)을 분산하면서 모델을 더욱 다양한 환경에 노출시킬 수 있다. 그러나 하드웨어(Hardware), 센서(Sensor), 제어 인터페이스(Control Interface)의 차이를 처리하려면 신중한 정규화(Normalization)와 신체 구조 인식 적응(Embodiment-Aware Adaptation)이 필요하다.

인간 피드백(Human Feedback)은 자율 학습(Autonomous Learning)이 어려운 상황에 직면했을 때 효율적인 지도(Supervision)를 제공할 수 있다. 운영자(Operator)는 궤적을 수정하거나, 복구 전략(Recovery Strategy)을 시연하거나, 안전하지 않은 행동(Unsafe Action)을 식별할 수 있다. 상호작용형 학습 시스템(Interactive Learning System)은 지속적인 감독을 요구하는 대신 필요한 경우에만 선택적으로 지원을 요청할 수 있다. 인간의 지침(Human Guidance)은 운영 비용(Operational Cost)을 발생시키고 일관성(Consistency)과 정밀도(Precision)가 달라질 수 있으므로 효과적인 피드백 인터페이스(Feedback Interface)를 설계하는 것이 중요하다.

데이터 효율적 학습(Data-Efficient Learning)의 평가는 최종 작업 성공(Final Task Success)만을 측정해서는 안 된다. 연구자는 목표 성능을 달성하는 데 필요한 물리적 상호작용 횟수(Number of Physical Interactions), 시연 시간(Demonstration Time), 인간 개입(Human Intervention), 장비 마모(Equipment Wear), 계산 자원(Computational Resource), 안전 사고(Safety Incident)를 고려해야 한다. 비교 평가(Comparison)는 일관된 데이터 예산(Data Budget)을 사용하고 시뮬레이션 경험(Simulated Experience)과 실제 세계 경험(Real-World Experience)을 명확하게 구분해야 한다. 익숙하지 않은 조건에 대한 일반화 역시 필수적인 평가 기준이다.

중요한 연구 방향은 사전 훈련된 모델(Pretrained Model), 시뮬레이션(Simulation), 능동 학습(Active Learning), 지속적 적응(Continual Adaptation)을 통합된 데이터 효율적 아키텍처(Unified Data-Efficient Architecture)로 결합하는 것이다. 각 방법은 물리적 데이터 수집(Physical Data Collection)의 서로 다른 한계를 해결한다. 이러한 방법을 결합하면 로봇은 폭넓은 사전 지식(Prior Knowledge)을 바탕으로 작동을 시작하고, 중요한 불확실성을 식별하며, 목표 지향적 경험(Targeted Experience)을 수집하고, 과도한 물리적 실험 없이 성능을 개선할 수 있을 것이다.

궁극적으로 제한된 실제 세계 데이터로부터의 학습은 부족한 물리적 경험(Scarce Physical Experience)을 재사용 가능하고 전이 가능한 지식(Reusable and Transferable Knowledge)으로 전환하는 것을 요구한다. 발전은 샘플 효율적인 알고리즘(Sample-Efficient Algorithm), 신뢰할 수 있는 월드 모델(Reliable World Model), 정보 가치가 높은 탐색(Informative Exploration), 고품질 데이터셋(High-Quality Dataset), 안전한 적응 메커니즘(Safe Adaptation Mechanism)에 달려 있다. 이러한 과제를 해결하면 피지컬 인공지능의 개발 비용을 줄이고, 광범위한 훈련이 현실적으로 어려운 환경에서도 자율 시스템(Autonomous System)이 새로운 능력을 습득할 수 있게 될 것이다.

## 07.08. Self Supervised and Weakly Supervised Robot Learning

![](images/image8.png){width="7.268055555555556in" height="7.268055555555556in"}

자기지도 로봇 학습(Self-Supervised Robot Learning)과 약지도 로봇 학습(Weakly Supervised Robot Learning)은 로봇이 비용이 많이 드는 인간 주석(Human Annotation)에 전적으로 의존하지 않고 유용한 지식을 획득해야 하므로 피지컬 인공지능(Physical AI)의 핵심 연구 방향이다. 물리적 환경(Physical Environment)은 시각(Visual), 촉각(Tactile), 고유수용감각(Proprioceptive), 행동(Action) 데이터의 연속적인 흐름을 생성한다. 이러한 신호로부터 학습하면 지도 정보(Supervision)에 대한 요구를 줄이면서 객체(Object), 동역학(Dynamics), 상호작용(Interaction)에 관한 표현(Representation)을 개발할 수 있다.

자기지도학습(Self-Supervised Learning)은 수동으로 부여된 레이블(Manually Assigned Label)에 의존하는 대신 사용 가능한 데이터에서 직접 훈련 목표(Training Objective)를 구성한다. 로봇은 미래 관측(Future Observation)을 예측하거나, 누락된 센서 측정값(Missing Sensor Measurement)을 복원하거나, 연속된 상태(Consecutive State) 사이의 관계를 추정할 수 있다. 이러한 작업은 일상적인 운영(Ordinary Operation)에서 학습 신호(Learning Signal)를 제공한다. 그러나 성공적인 복원(Reconstruction)이나 예측(Prediction)이 결과적으로 얻어진 표현이 신뢰할 수 있는 물리적 행동(Physical Action)을 지원한다는 것을 자동으로 보장하지는 않는다.

약지도학습(Weakly Supervised Learning)은 불완전하거나(Incomplete), 잡음이 포함되거나(Noisy), 대략적이거나(Coarse), 간접적으로 연결된 레이블(Indirectly Associated Label)을 사용하여 모델 훈련(Model Training)을 안내한다. 로봇 데이터셋(Robot Dataset)에는 정밀한 행동 수준 주석(Action-Level Annotation) 없이 작업 설명(Task Description), 대략적인 객체 위치(Approximate Object Location), 성공 지표(Success Indicator), 인간 지시(Human Instruction)가 포함될 수 있다. 이러한 정보는 유용한 의미적 구조(Semantic Structure)를 제공할 수 있다. 핵심 과제는 주석 오류(Annotation Error)가 체계적인 행동 오류(Systematic Behavioral Mistake)로 발전하지 않도록 하면서 신뢰할 수 있는 학습 신호를 추출하는 것이다.

로봇 학습(Robot Learning)은 물리적 능력(Physical Competence)을 확보하기 위해 행동이 환경을 어떻게 변화시키는지 이해해야 한다는 점에서 기존의 이미지 표현 학습(Image Representation Learning)과 다르다. 시각적 유사성(Visual Similarity)만으로는 객체를 파지(Grasping)할 수 있는지, 안정적인지, 이동 가능한지, 깨지기 쉬운지 판단할 수 없다. 따라서 자기지도 학습 목표(Self-Supervised Objective)는 관측(Observation)을 모터 명령(Motor Command) 및 그에 따른 상태 전이(State Transition)와 연결해야 한다. 이러한 행동 조건부 구조(Action-Conditioned Structure)는 물리적으로 의미 있는 표현(Physically Meaningful Representation)을 학습하는 데 필수적이다.

시간적 예측(Temporal Prediction)은 체화 시스템(Embodied System)에 자연스러운 자기지도 신호(Self-Supervision Signal)를 제공한다. 로봇은 이전 상태(Previous State)와 행동을 바탕으로 미래 관측을 추정함으로써 움직임(Motion), 상호작용, 환경 변화(Environmental Change)의 패턴을 학습할 수 있다. 단기 예측(Short-Term Prediction)은 즉각적인 동역학(Immediate Dynamics)을 포착하고, 장기 예측 구간(Longer Prediction Horizon)은 작업 진행(Task Progression)과 지연된 결과(Delayed Consequence)를 드러낸다. 여러 시간 척도(Multiple Timescale)에 걸쳐 정확성을 유지하는 것은 여전히 중요한 과제이다.

마스킹 센서 모델링(Masked Sensor Modeling)은 의도적으로 숨겨진 관측 부분(Hidden Observation)을 복원함으로써 로봇이 학습할 수 있도록 한다. 누락된 이미지 영역(Missing Image Region), 깊이 측정값(Depth Measurement), 촉각 측정값(Tactile Reading), 고유수용감각 신호(Proprioceptive Signal)는 주변 정보(Surrounding Information)로부터 예측할 수 있다. 이는 모델이 센싱 양식(Sensing Modality) 사이의 관계를 발견하도록 유도한다. 그러나 복원 품질(Reconstruction Quality)은 물리적 이해(Physical Understanding)의 충분한 증거로 간주하기보다 후속 제어 성능(Downstream Control Performance)을 기준으로 평가해야 한다.

다중모달 자기지도학습(Multimodal Self-Supervision)은 로봇 인식(Robotic Perception)이 상호 보완적인 정보원(Complementary Information Source)을 결합하기 때문에 특히 중요하다. 카메라(Camera)는 외관(Appearance)과 기하학(Geometry)을 제공하고, 촉각 센서(Tactile Sensor)는 접촉 특성(Contact Property)을 드러내며, 고유수용감각 측정값(Proprioceptive Measurement)은 내부 움직임(Internal Motion)을 설명한다. 이러한 신호를 정렬(Alignment)하면 로봇이 숨겨진 물리적 상태(Hidden Physical State)를 추론하는 데 도움이 된다. 어려움은 이질적인 데이터(Heterogeneous Data)를 동기화(Synchronization)하고 의미 있는 관계를 우연한 상관관계(Accidental Correlation)와 구분하는 데 있다.

대조 학습(Contrastive Learning)은 관련된 관측과 행동이 표현 공간(Representation Space)에서 서로 가까운 영역을 차지하도록 유도하여 로봇 경험(Robot Experience)을 구조화할 수 있다. 동일한 객체의 서로 다른 시점(Different View)이나 하나의 상호작용에서 발생한 연속 상태(Consecutive State)는 긍정적 연관성(Positive Association)을 제공할 수 있다. 관련 없는 경험은 대조 사례(Contrasting Example)로 활용될 수 있다. 그러나 훈련 쌍(Training Pair)을 부적절하게 선택하면 중요한 물리적 차이(Physical Difference)를 억제하면서 시각적 불변성(Visual Invariance)만 강화할 수 있다.

행동 조건부 표현 학습(Action-Conditioned Representation Learning)은 환경이 로봇 행동에 어떻게 반응하는지를 결정하는 정보를 보존하는 것을 목표로 한다. 두 객체는 외관이 비슷하더라도 재료(Material)나 질량(Mass)의 차이 때문에 서로 다른 파지력(Gripping Force)이 필요할 수 있다. 유용한 표현은 이러한 차이가 제어 결정(Control Decision)에 영향을 줄 때 두 사례를 구별해야 한다. 이는 외관만이 아니라 행동 결과(Action Outcome), 제어 가능성(Controllability), 물리적 결과(Physical Consequence)를 기반으로 학습 목표를 설계해야 할 필요성을 보여준다.

예측 월드 모델(Predictive World Model)은 자기지도 로봇 학습을 위한 통합 프레임워크(Unified Framework)를 제공한다. 모델은 미래 잠재 상태(Future Latent State), 객체 궤적(Object Trajectory), 접촉 사건(Contact Event), 작업 관련 환경 변화(Task-Relevant Environmental Change)를 추정할 수 있다. 일단 학습되면 이러한 모델은 모든 행동 시퀀스(Action Sequence)에 대한 직접적인 지도 없이도 계획(Planning)을 지원할 수 있다. 그러나 누적된 예측 오차(Accumulated Prediction Error)와 불확실한 물리적 상호작용(Uncertain Physical Interaction)은 장기 작업 실행(Long-Horizon Execution)에서 신뢰성을 저하시킬 수 있다.

객체 영속성(Object Permanence)과 지속적인 환경 구조(Persistent Environmental Structure)를 학습하는 것도 중요한 목표이다. 로봇은 가림(Occlusion), 부분적 가시성(Partial Visibility), 일시적인 센서 손실(Temporary Sensor Loss)을 자주 경험한다. 시간에 따른 자기지도 추적(Self-Supervised Tracking)은 객체 정체성(Object Identity)과 공간적 관계(Spatial Relationship)를 유지하는 표현의 학습을 촉진할 수 있다. 그러나 객체는 관측되지 않은 상호작용(Unobserved Interaction)을 통해 이동하거나 변화할 수도 있으므로, 모델은 환경이 완전히 안정적이라고 가정하기보다 불확실성(Uncertainty)을 표현해야 한다.

약지도학습(Weak Supervision)은 대규모 인간 영상 데이터(Human Video Data)를 로봇 기술 습득(Robotic Skill Acquisition)과 연결할 수 있다. 영상에는 의미 있는 행동을 나타내는 언어 설명(Language Description), 행동 범주(Action Category), 대략적인 시간적 경계(Approximate Temporal Boundary)가 포함될 수 있다. 이러한 신호는 조작 시퀀스(Manipulation Sequence)와 작업 구조(Task Structure)에 관한 학습을 지원한다. 그러나 인간 행동(Human Action)은 로봇 행동(Robot Action)과 다르며, 시각적 시연(Visual Demonstration)은 정확한 힘(Force), 접촉 조건(Contact Condition), 실행 가능한 제어 명령(Executable Control Command)을 제공하는 경우가 드물다.

언어(Language)는 관측과 행동 시퀀스를 의미적 설명(Semantic Description)에 연결함으로써 유연한 약지도 정보(Weak Supervision)를 제공한다. 로봇은 서랍 열기(Opening a Drawer)가 손잡이에 접근하고, 접촉을 형성하며, 제한된 방향(Constrained Direction)을 따라 당기는 과정이라는 것을 학습할 수 있다. 이러한 설명은 작업 분해(Task Decomposition)와 기술 검색(Skill Retrieval)을 지원할 수 있다. 그러나 언어적 지식(Linguistic Knowledge)은 물리적 실행 가능성(Physical Feasibility)에 기반해야 하며 감각 피드백(Sensory Feedback)을 통해 검증되어야 한다.

작업 성공과 실패(Task Success and Failure)로부터의 학습은 또 다른 약지도 정보원을 제공한다. 이진 성공 지표(Binary Success Indicator)는 매 순간의 올바른 행동을 지정하지 않고도 완료된 작업과 실패한 시도를 구분할 수 있다. 모델은 이러한 결과를 활용하여 정책 선택(Policy Selection)을 개선하거나 효과적인 행동 패턴(Effective Behavior Pattern)을 식별할 수 있다. 그러나 긴 행동 시퀀스에 유용한 결정과 해로운 결정이 함께 포함되어 있으면 희소 피드백(Sparse Feedback)은 신용 할당 문제(Credit Assignment Problem)를 발생시킨다.

비지도 기술 발견(Unsupervised Skill Discovery)은 사전에 정의된 작업 레이블(Predefined Task Label) 없이 재사용 가능한 행동(Reusable Behavior)을 식별하는 것을 목표로 한다. 로봇은 행동 다양성(Behavioral Diversity)이나 제어 가능한 상태 변화(Controllable State Change)를 최대화함으로써 움직임 패턴(Movement Pattern), 객체 상호작용(Object Interaction), 탐색 전략(Exploration Strategy)을 학습할 수 있다. 이러한 기술은 미래 작업을 위한 구성 요소(Building Block)가 될 수 있다. 핵심 과제는 발견된 행동이 단순히 훈련 환경(Training Environment)에서 다양하기만 한 것이 아니라 의미 있고 안전하며 전이 가능하도록 보장하는 것이다.

내재적 동기(Intrinsic Motivation)는 로봇이 내부 이해(Internal Understanding)를 향상시키는 상황을 탐색하도록 유도할 수 있다. 예측 오차(Prediction Error), 정보 이득(Information Gain), 학습 진전(Learning Progress)은 정보 가치가 높은 행동(Informative Action)을 선택하기 위한 신호로 활용될 수 있다. 로봇은 통제된 실험(Controlled Experiment)을 통해 익숙하지 않은 재료(Unfamiliar Material)를 조사하거나 불확실한 객체 상호작용(Uncertain Object Interaction)을 시험할 수 있다. 그러나 호기심 기반 탐색(Curiosity-Driven Exploration)은 위험한 행동과 예측 불가능한 잡음(Unpredictable Noise)을 반복적으로 추구하는 현상을 방지하도록 제약되어야 한다.

오프라인 로봇 데이터셋(Offline Robotic Dataset)은 추가적인 물리적 실험 없이 기록된 센서 스트림(Recorded Sensor Stream)을 재사용할 수 있으므로 자기지도학습에 상당한 기회를 제공한다. 운영 로그(Operational Log), 원격조작 시연(Teleoperation Demonstration), 플릿 경험(Fleet Experience)에는 풍부한 시간적 정보(Temporal Information)가 포함될 수 있다. 그러나 이러한 데이터셋은 일관되지 않은 센서 구성(Inconsistent Sensor Configuration)과 편향된 작업 범위(Biased Task Coverage)를 보이는 경우가 많다. 잘못된 표현(Misleading Representation)의 학습을 방지하려면 신중한 데이터 큐레이션(Data Curation)이 필요하다.

시뮬레이션(Simulation)은 다양한 상호작용을 생성하고 물리적 상태 정보(Physical State Information)를 자동으로 제공함으로써 실제 세계 자기지도학습(Real-World Self-Supervision)을 보완할 수 있다. 합성 궤적(Synthetic Trajectory)은 기하학(Geometry), 재료 특성(Material Property), 접촉 조건(Contact Condition), 환경 교란(Environmental Disturbance)의 변화에 모델을 노출시킬 수 있다. 그러나 모델은 시뮬레이션에 특화된 인공적 특성(Simulation Artifact)을 학습할 수 있다. 시뮬레이션 관측과 물리적 관측을 결합하려면 도메인 차이(Domain Difference)를 보정하면서 전이 가능한 동역학(Transferable Dynamics)을 보존하는 방법이 필요하다.

지속적 자기지도학습(Continual Self-Supervised Learning)은 배치된 로봇(Deployed Robot)이 일상적인 운영을 통해 성능을 개선하도록 할 수 있다. 새로운 관측은 익숙한 객체(Familiar Object), 변화하는 환경(Changing Environment), 이전에 경험하지 못한 상호작용(Previously Unseen Interaction)에 관한 표현을 정교화할 수 있다. 이러한 학습은 반복적인 인간 레이블링(Human Labeling)에 대한 의존성을 줄인다. 그러나 통제되지 않은 모델 업데이트(Uncontrolled Model Update)는 치명적 망각(Catastrophic Forgetting)을 발생시키거나 기존 기술(Established Skill)을 저하시킬 수 있으므로 검증(Validation)과 보호된 적응 메커니즘(Protected Adaptation Mechanism)이 필요하다.

불확실성 추정(Uncertainty Estimation)은 지도 정보(Supervision)가 불완전할 때 특히 중요하다. 약지도 레이블(Weak Label)에는 오류가 포함될 수 있으며, 자기지도 학습 목표(Self-Supervised Objective)는 여러 가지 그럴듯한 해석(Plausible Interpretation)을 허용할 수 있다. 모델은 확신할 수 있는 지식(Confident Knowledge)과 불확실한 가정(Uncertain Assumption)을 구별하고, 생성된 모든 예측을 동일하게 신뢰할 수 있는 것으로 취급하지 않아야 한다. 보정(Calibration), 앙상블 방법(Ensemble Method), 선택적 인간 검토(Selective Human Review)는 잘못된 학습 신호가 운영에 미치는 영향을 줄이는 데 도움이 될 수 있다.

평가(Evaluation)는 자기지도 표현(Self-Supervised Representation)이 실제 로봇 능력(Actual Robotic Capability)을 향상시키는지 판단해야 한다. 복원(Reconstruction), 대조 학습(Contrastive Learning), 예측(Prediction) 목표에서 높은 성능을 달성했다고 해서 성공적인 조작(Manipulation)이나 내비게이션(Navigation)이 반드시 보장되는 것은 아니다. 벤치마크(Benchmark)는 후속 작업 성능(Downstream Task Performance), 샘플 효율성(Sample Efficiency), 익숙하지 않은 조건으로의 전이(Transfer), 강건성(Robustness), 안전성(Safety)을 측정해야 한다. 또한 비교 평가에서는 주석 비용(Annotation Cost)과 사용된 비레이블 데이터(Unlabeled Data)의 양을 고려해야 한다.

중요한 미해결 질문(Open Question)은 어떤 자기지도 학습 목표(Self-Supervised Objective)가 물리적 추론(Physical Reasoning)에 진정으로 유용한 표현을 생성하는가에 관한 것이다. 픽셀(Pixel), 잠재 상태(Latent State), 접촉 결과(Contact Outcome), 미래 보상(Future Reward)을 예측하는 것은 각각 경험의 서로 다른 측면을 강조한다. 어떤 단일 목표도 관련된 모든 물리적 정보(Relevant Physical Information)를 보존한다고 보장할 수 없다. 연구에서는 기하학(Geometry), 동역학(Dynamics), 인과성(Causality), 제어 가능성(Controllability), 장기 작업 구조(Long-Term Task Structure)를 포착하는 목표의 조합을 탐색해야 한다.

궁극적으로 자기지도 로봇 학습(Self-Supervised Robot Learning)과 약지도 로봇 학습(Weakly Supervised Robot Learning)은 풍부하지만 불완전한 감각 경험(Abundant but Imperfect Sensory Experience)을 신뢰할 수 있는 물리 지능(Reliable Physical Intelligence)으로 전환하는 것을 목표로 한다. 발전을 위해서는 의미 있는 훈련 목표(Meaningful Training Objective), 다중모달 기반화(Multimodal Grounding), 잡음이 포함된 지도 정보(Noisy Supervision)의 강건한 처리(Robust Handling), 상호작용을 통한 지속적인 검증(Continual Validation Through Interaction)이 필요하다. 이러한 발전은 비용이 많이 드는 주석(Costly Annotation)에 대한 의존도를 줄이고, 피지컬 인공지능 시스템이 일상적인 경험(Everyday Experience)으로부터 점점 더 범용적인 능력(General Capability)을 학습하도록 할 수 있을 것이다.

## 07.09. Continual and Lifelong Learning

![](images/image9.png){width="7.268055555555556in" height="7.268055555555556in"}

지속 학습(Continual Learning)과 평생 학습(Lifelong Learning)은 시간이 지남에 따라 변화하는 환경에서 작동하는 피지컬 인공지능(Physical AI) 시스템에 필수적인 능력이다. 한 번 훈련된 후 고정된 매개변수(Fixed Parameter)로 배포되는 기존 머신러닝 모델(Conventional Machine Learning Model)과 달리 자율 로봇(Autonomous Robot)은 새로운 객체, 작업, 사용자, 물리적 조건에 적응해야 한다. 평생 학습은 운영 전반에 걸쳐 유용한 경험을 축적하면서 이전에 획득한 지식을 보존하고 신뢰할 수 있는 행동을 유지하는 것을 목표로 한다.

실제 세계 환경(Real-World Environment)은 객체가 이동하고, 장비가 노후화되며, 공간 배치가 변화하고, 인간 활동이 발전하기 때문에 본질적으로 비정상적(Nonstationary)이다. 창고 로봇(Warehouse Robot)은 새로운 재고 배치(Inventory Configuration)를 마주할 수 있으며, 서비스 로봇(Service Robot)은 익숙하지 않은 가정 내 배치(Household Arrangement)에 직면할 수 있다. 고정 정책(Fixed Policy)은 이러한 조건에서 점차 효과가 감소할 수 있다. 지속 학습은 운영 환경(Operational Circumstance)이 변화함에 따라 로봇 시스템이 내부 표현(Internal Representation)과 제어 전략(Control Strategy)을 갱신할 수 있도록 한다.

핵심 과제는 학습 과정에서 안정성(Stability)과 가소성(Plasticity)의 균형을 유지하는 것이다. 안정성은 기존 지식(Established Knowledge)과 신뢰할 수 있는 기술(Reliable Skill)을 보존하고, 가소성은 익숙하지 않은 경험에 대한 적응(Adaptation)을 가능하게 한다. 지나친 안정성은 개선을 방해하고, 지나친 가소성은 이전에 성공적으로 수행하던 행동을 손상시킬 수 있다. 효과적인 평생 학습은 여전히 유효한 지식을 불필요하게 수정하지 않으면서 새로운 정보를 선택적으로 통합하는 메커니즘(Mechanism)을 필요로 한다.

치명적 망각(Catastrophic Forgetting)은 새로운 작업을 학습하는 과정에서 모델이 이전에 숙달한 작업(Previously Mastered Task)의 성능을 잃는 현상이다. 이 문제는 잊힌 기술이 위험한 물리적 행동(Unsafe Physical Behavior)을 유발할 수 있으므로 로봇공학(Robotics)에서 특히 심각하다. 새로운 파지 전략(Grasping Strategy)에 적응하는 로봇은 익숙한 객체를 안정적으로 다루는 능력을 잃어서는 안 된다. 망각을 방지하려면 연속적인 학습 단계(Successive Learning Stage) 전반에 걸쳐 중요한 표현(Representation), 행동(Behavior), 안전 제약(Safety Constraint)을 보존해야 한다.

경험 재생(Experience Replay)은 이전 지식을 유지하기 위한 하나의 접근법이다. 로봇은 과거 작업에서 선택된 관측(Observation), 행동(Action), 결과(Outcome)를 저장하고 이후 훈련에서 재사용한다. 재생 버퍼(Replay Buffer)에는 대표적인 성공 사례(Representative Success), 드문 실패(Rare Failure), 중요한 복구 행동(Recovery Behavior)이 포함될 수 있다. 그러나 저장 용량(Storage Capacity)과 계산 자원(Computational Resource)은 제한되어 있으므로 기억 선택(Memory Selection)과 효율적인 샘플링(Efficient Sampling)이 중요한 연구 문제가 된다.

정규화 기반 방법(Regularization-Based Method)은 이전 작업에 중요하다고 판단되는 매개변수(Parameter)의 변화를 제한하여 망각을 줄인다. 이러한 접근법은 기존 능력(Established Capability)을 손상시킬 수 있는 수정을 억제하면서 모델의 적응을 허용한다. 효과는 어떤 매개변수가 가치 있는 지식(Valuable Knowledge)을 지원하는지 정확하게 식별하는 능력에 달려 있다. 복잡한 로봇 작업(Complex Robotic Task)은 표현을 공유하는 경우가 많으므로 재사용 가능한 지식(Reusable Knowledge)과 작업별 지식(Task-Specific Knowledge)을 구분하기 어렵다.

모듈형 학습 아키텍처(Modular Learning Architecture)는 지속적 적응(Continual Adaptation)을 위한 또 다른 전략을 제공한다. 인식 모듈(Perception Module), 월드 모델(World Model), 기술 라이브러리(Skill Library), 저수준 제어기(Low-Level Controller)는 적절한 경우 독립적으로 갱신될 수 있다. 로봇은 전체 내비게이션 시스템(Navigation System)을 교체하지 않고도 새로운 조작 기술(Manipulation Skill)을 학습할 수 있다. 그러나 모듈 사이의 상호작용은 예상하지 못한 의존성(Unexpected Dependency)을 생성할 수 있으므로 신중한 통합 시험(Integration Testing)과 호환성 관리(Compatibility Management)가 필요하다.

평생 로봇 학습(Lifelong Robot Learning)은 실제 환경 변화(Genuine Environmental Change)를 일시적인 교란(Temporary Disturbance) 및 센서 잡음(Sensor Noise)과 구분해야 한다. 미끄러운 바닥(Slippery Floor)은 표면 조건(Surface Condition)의 지속적인 변화일 수도 있고 일시적인 오염 사건(Contamination Event)일 수도 있다. 정책을 지나치게 공격적으로 갱신하면 정상 조건이 복구된 후 성능이 저하될 수 있다. 변화 감지(Change Detection), 불확실성 추정(Uncertainty Estimation), 시간적 추론(Temporal Reasoning)은 언제 적응이 필요한지, 새로운 지식을 얼마나 오래 유지해야 하는지 결정하는 데 도움이 된다.

온라인 학습(Online Learning)은 로봇이 일상적인 운영 중 수집한 데이터를 사용하여 모델을 갱신할 수 있도록 한다. 연속적인 관측(Continuous Observation)은 마찰(Friction), 탑재 하중 분포(Payload Distribution), 액추에이터 응답(Actuator Response), 객체 거동(Object Behavior)의 변화를 드러낼 수 있다. 이러한 갱신은 전체 재훈련(Complete Retraining) 없이 성능을 향상시킬 수 있다. 그러나 온라인 적응(Online Adaptation)은 특히 실시간 제어(Real-Time Control)와 동시에 학습이 이루어지는 경우 계산 및 안전 제약(Computational and Safety Constraint) 내에서 작동해야 한다.

자기지도학습(Self-Supervised Learning)은 로봇이 지속적으로 감각 경험(Sensory Experience)을 생성하기 때문에 평생 적응(Lifelong Adaptation)에 유용한 신호를 제공한다. 미래 관측(Future Observation)을 예측하고, 접촉 결과(Contact Outcome)를 추정하며, 예상하지 못한 상태 전이(Unexpected State Transition)를 감지하는 것은 광범위한 수동 주석(Manual Annotation) 없이 표현 갱신(Representation Update)을 지원할 수 있다. 그러나 자기지도 학습 목표(Self-Supervised Objective)는 관련성이 낮은 패턴(Irrelevant Pattern)을 강화할 수 있다. 학습 시스템은 갱신된 표현이 의미 있는 물리적 능력(Meaningful Physical Capability)을 향상시키는지 검증해야 한다.

지속적 월드 모델 학습(Continual World Model Learning)은 새로운 증거가 확보됨에 따라 로봇이 환경 동역학(Environmental Dynamics)에 관한 예측을 정교화할 수 있도록 한다. 매니퓰레이터(Manipulator)는 익숙하지 않은 재료(Unfamiliar Material)의 특성을 점진적으로 추정할 수 있으며, 모바일 로봇(Mobile Robot)은 변화하는 지형(Changing Terrain)에 대한 이해를 향상시킬 수 있다. 이러한 모델은 계획(Planning)과 적응을 지원한다. 모델의 신뢰성(Reliability)은 불확실성을 관리하고 잘못된 갱신(Incorrect Update)이 기존 물리적 지식(Established Physical Knowledge)을 오염시키지 않도록 방지하는 데 달려 있다.

기술 축적(Skill Accumulation)은 평생 물리 지능(Lifelong Physical Intelligence)의 핵심 목표이다. 로봇은 모든 작업을 독립적으로 학습하는 대신 재사용 가능한 기술(Reusable Skill)을 보존하고 결합하여 점점 더 복잡한 문제를 해결해야 한다. 파지(Grasping), 위치 조정(Positioning), 열기(Opening), 운반(Transporting), 검사(Inspection) 행동은 더 큰 작업 시퀀스(Task Sequence)의 구성 요소가 될 수 있다. 효과적인 기술 라이브러리(Skill Library)를 위해서는 기술 발견(Skill Discovery), 선택(Selection), 개선(Refinement), 신뢰할 수 있는 조합(Reliable Composition)을 위한 메커니즘이 필요하다.

작업 간 지식 전이(Knowledge Transfer Across Tasks)는 공통된 물리적 구조(Common Physical Structure)를 활용하여 지속 학습을 가속할 수 있다. 한 종류의 용기(Container)를 다룬 경험은 다른 용기를 조작하는 데 도움이 될 수 있으며, 접촉력(Contact Force)에 관한 지식은 여러 조립 작업(Assembly Operation)에 일반화될 수 있다. 긍정적 전이(Positive Transfer)는 데이터 요구량(Data Requirement)을 줄이지만, 부적절한 가정(Inappropriate Assumption)을 재사용하면 부정적 전이(Negative Transfer)가 발생할 수 있다. 로봇은 이전에 학습한 지식이 새로운 상황에 적용 가능한지 평가해야 한다.

장기 기억 시스템(Long-Term Memory System)은 로봇 경험(Robotic Experience)을 여러 추상화 수준(Level of Abstraction)에서 조직할 수 있다. 일화 기억(Episodic Memory)은 구체적인 상호작용과 결과를 보존하고, 의미 기억(Semantic Memory)은 객체와 환경에 관한 일반화된 지식(Generalized Knowledge)을 저장한다. 절차 기억(Procedural Memory)은 재사용 가능한 기술과 제어 전략(Control Strategy)을 표현한다. 이러한 기억 형태를 조정하면 학습 효율성(Learning Efficiency)을 향상시킬 수 있지만, 무엇을 유지하고 요약하며 폐기할지 결정하는 것은 여전히 어렵다.

능동 학습(Active Learning)은 추가 경험이 가치 있는 상황을 식별함으로써 평생 적응의 효율성을 높일 수 있다. 로봇은 불확실성을 줄이기 위해 인간의 지원(Human Assistance)을 요청하거나, 익숙하지 않은 객체를 검사하거나, 통제된 실험(Controlled Experiment)을 수행할 수 있다. 이러한 전략은 무분별한 탐색(Indiscriminate Exploration)을 방지한다. 그러나 정보 탐색 행동(Information-Seeking Action)은 운영 목표(Operational Objective) 및 물리적 안전 요구사항(Physical Safety Requirement)과 양립할 수 있어야 한다.

인간 피드백(Human Feedback)은 자율 학습(Autonomous Learning)이 모호하거나 위험도가 높은 상황(Ambiguous or High-Risk Situation)에 직면할 때 중요하다. 운영자(Operator)는 시연(Demonstration)을 제공하거나, 실패한 행동(Unsuccessful Behavior)을 교정하거나, 환경 변화가 의미 있는지 확인할 수 있다. 선택적 감독(Selective Supervision)은 지속적인 인간 개입(Continuous Human Involvement) 없이 적응을 향상시킬 수 있다. 핵심 과제는 개입(Intervention)에 대한 과도한 의존을 피하면서 피드백을 일관되게 통합하는 것이다.

다중 로봇 평생 학습(Multi-Robot Lifelong Learning)은 집단적 지식 축적(Collective Knowledge Accumulation)의 기회를 제공한다. 서로 다른 장소에서 작동하는 로봇은 각기 다른 객체, 환경 조건(Environmental Condition), 실패 패턴(Failure Pattern)을 경험할 수 있다. 공유 경험(Shared Experience)은 플릿(Fleet) 전체의 학습을 가속할 수 있다. 그러나 신체 구조(Embodiment), 센싱(Sensing), 운영 맥락(Operational Context)의 차이로 인해 한 플랫폼에서 학습한 지식을 다른 플랫폼에 적용하기 전에 신중한 적응이 필요하다.

연합 학습(Federated Learning)과 분산 학습(Distributed Learning)은 모든 원시 관측(Raw Observation)을 중앙에 집중시키지 않고도 지식 공유를 지원할 수 있다. 로봇은 민감한 운영 데이터(Sensitive Operational Data)를 로컬(Local)에 유지하면서 선택된 모델 업데이트(Model Update)나 요약된 경험(Summarized Experience)을 교환할 수 있다. 이러한 시스템은 통신 제약(Communication Limitation), 이질적인 데이터 분포(Heterogeneous Data Distribution), 상충하는 업데이트(Conflicting Update)를 해결해야 한다. 또한 공유된 개선 사항(Shared Improvement)이 배포된 플릿 전체로 오류를 확산시키지 않도록 검증이 필요하다.

안전 보증(Safety Assurance)은 배포(Deployment) 이후 로봇 행동이 변화할 때 점점 더 어려워진다. 초기 시험(Initial Testing)에서 검증된 정책(Validated Policy)은 광범위한 적응 이후 더 이상 동일하게 작동하지 않을 수 있다. 따라서 지속 학습 시스템은 모니터링(Monitoring), 통제된 업데이트 절차(Controlled Update Procedure), 롤백 메커니즘(Rollback Mechanism), 독립적인 안전 제약(Independent Safety Constraint)을 필요로 한다. 위험도가 높은 변경(High-Risk Change)은 최근 훈련 성능이 향상되었다는 이유만으로 수용하지 말고 활성화(Activation) 전에 평가해야 한다.

평생 학습의 평가(Evaluation of Lifelong Learning)는 최신 작업(Newest Task)의 성능을 넘어 이루어져야 한다. 벤치마크(Benchmark)는 이전 기술의 유지(Retention of Previous Skills), 적응 속도(Adaptation Speed), 누적 작업 성공률(Cumulative Task Success), 전이 효율성(Transfer Efficiency), 환경 변화로부터의 복구(Recovery from Environmental Changes)를 측정해야 한다. 점진적인 성능 저하(Gradual Degradation)와 숨겨진 간섭(Hidden Interference)을 발견하려면 장기간 시험(Long-Duration Testing)이 필요하다. 또한 평가는 학습에 필요한 물리적 상호작용 비용(Physical Interaction Cost)과 안전성에 미치는 영향(Safety Implication)을 고려해야 한다.

주요 미해결 연구 질문(Open Research Question)은 자율 로봇이 언제 학습하고, 언제 기존 행동을 보존하며, 언제 지원을 요청해야 하는지를 어떻게 결정할 것인가에 관한 것이다. 지속적인 업데이트(Continuous Updating)가 항상 유익한 것은 아니며, 특히 관측이 신뢰할 수 없거나 운영 조건이 일시적인 경우에는 더욱 그렇다. 지능형 학습 관리(Intelligent Learning Management)를 위해서는 보정된 불확실성(Calibrated Uncertainty), 작업 인식(Task Awareness), 자원 할당(Resource Allocation), 안전성과 장기 성능(Long-Term Performance)에 대한 명시적인 고려가 필요하다.

또 다른 과제는 변화하는 표현과 모델 사이에서 지식 일관성(Knowledge Consistency)을 유지하는 것이다. 새로운 인식 시스템(Perception System)은 객체를 다르게 분류할 수 있으며, 갱신된 월드 모델(World Model)은 예측된 행동 결과(Predicted Action Outcome)를 변경할 수 있다. 이전에 학습한 기술은 이러한 변화와 계속 호환되어야 한다. 버전 관리된 표현(Versioned Representation), 모듈형 인터페이스(Modular Interface), 체계적인 회귀 시험(Systematic Regression Testing)은 불일치(Inconsistency)가 축적된 능력(Accumulated Competence)을 손상시키는 것을 방지하는 데 도움이 될 수 있다.

궁극적으로 지속 학습(Continual Learning)과 평생 학습(Lifelong Learning)은 피지컬 인공지능을 고정된 훈련 능력(Fixed Trained Capability)의 집합에서 물리적 세계(Physical World)와의 지속적인 상호작용(Sustained Interaction)을 통해 개선되는 시스템으로 전환하는 것을 목표로 한다. 이러한 비전을 실현하려면 안정적인 지식 유지(Stable Knowledge Retention), 적응형 표현(Adaptive Representation), 구조화된 기억(Structured Memory), 안전한 온라인 학습(Safe Online Learning), 신뢰할 수 있는 평가(Reliable Evaluation)가 필요하다. 이러한 발전은 로봇이 기존 능력을 희생하지 않으면서 수년에 걸쳐 경험을 축적하고 점점 더 높은 수준의 능력을 갖추도록 할 것이다.

## 07.10. Catastrophic Forgetting and Knowledge Accumulation

![](images/image10.png){width="7.268055555555556in" height="7.268055555555556in"}

치명적 망각(Catastrophic Forgetting)과 지식 축적(Knowledge Accumulation)은 자율 로봇(Autonomous Robot)이 이전에 학습한 기술(Previously Learned Skill)을 잃지 않으면서 새로운 능력(New Capability)을 습득해야 한다는 점에서 피지컬 인공지능(Physical AI)의 상호 연결된 과제이다. 정적 학습 시스템(Static Learning System)과 달리 배포된 로봇(Deployed Robot)은 운영 수명(Operational Life) 전반에 걸쳐 변화하는 작업, 환경, 물리적 조건에 직면한다. 신뢰할 수 있는 지능(Reliable Intelligence)을 위해서는 기존 능력(Established Competence)을 보존하면서 새로운 경험을 확장 가능한 재사용 지식(Reusable Knowledge) 체계에 통합하는 메커니즘(Mechanism)이 필요하다.

치명적 망각(Catastrophic Forgetting)은 새로운 경험에 대한 훈련이 이전 작업(Earlier Task)의 성능을 크게 저하시키는 현상이다. 신경망(Neural Network)은 새로운 정보를 수용하기 위해 공유 매개변수(Shared Parameter)가 수정될 수 있으므로 이러한 문제에 특히 취약하다. 익숙하지 않은 객체(Unfamiliar Object)를 조작하는 방법을 학습하는 로봇은 결과적으로 익숙한 객체(Familiar Object)를 다룰 때 정밀도(Precision)를 잃을 수 있다. 이러한 성능 저하는 잊힌 행동이 안전 필수 제어(Safety-Critical Control)나 복구 절차(Recovery Procedure)와 관련될 때 특히 우려된다.

안정성-가소성 딜레마(Stability-Plasticity Dilemma)는 기존 지식(Existing Knowledge)을 보존하는 것과 새로운 정보(New Information)에 적응하는 것 사이의 긴장 관계를 설명한다. 지나친 안정성(Stability)은 로봇이 익숙하지 않은 작업을 학습하지 못하게 하고, 지나친 가소성(Plasticity)은 최근 경험이 가치 있는 표현(Valuable Representation)을 덮어쓰도록 만든다. 효과적인 학습 시스템은 어떤 지식을 안정적으로 유지하고 어떤 구성 요소(Component)를 적응시켜야 하는지 결정해야 한다. 이러한 결정은 작업 다양성(Task Diversity)과 운영 경험(Operational Experience)이 증가할수록 더욱 어려워진다.

망각(Forgetting)은 인식(Perception), 계획(Planning), 월드 모델링(World Modeling), 운동 제어(Motor Control)에 서로 다른 방식으로 영향을 미칠 수 있다. 인식 모델(Perception Model)은 이전에 경험한 객체를 인식하는 능력을 잃을 수 있으며, 제어기(Controller)는 성공적인 파지 전략(Grasping Strategy)을 잊을 수 있다. 월드 모델(World Model) 역시 정확한 물리적 관계(Physical Relationship)를 최근 환경에서 도출된 가정(Assumption)으로 대체할 수 있다. 이러한 서로 다른 실패 메커니즘(Failure Mechanism)을 이해하는 것은 목표 지향적인 지식 보존 방법(Knowledge-Preservation Method)을 설계하는 데 필요하다.

경험 재생(Experience Replay)은 치명적 망각을 줄이기 위해 널리 연구되는 접근법이다. 로봇은 이전 작업에서 선택된 궤적(Trajectory), 관측(Observation), 행동(Action), 결과(Outcome)를 보존하고 이후 훈련에 통합한다. 대표적인 경험(Representative Experience)을 재생하면 새로운 기술을 습득하는 동안 이전 능력(Earlier Capability)을 유지하는 데 도움이 된다. 그러나 물리적 상호작용 기록(Physical Interaction Record)은 용량이 클 수 있으므로 기억 용량(Memory Capacity), 데이터 선택(Data Selection), 재생 빈도(Replay Frequency)가 중요한 설계 고려사항이 된다.

기억 선택(Memory Selection)은 자주 관측되는 행동 이상의 정보를 우선적으로 고려해야 한다. 드문 실패(Rare Failure), 성공적인 복구 시퀀스(Successful Recovery Sequence), 특이한 접촉 조건(Unusual Contact Condition), 안전 필수 상호작용(Safety-Critical Interaction)은 상대적으로 높은 정보 가치를 포함할 수 있다. 대표성 기반 샘플링(Representative Sampling)은 폭넓은 작업 범위(Task Coverage)를 보존할 수 있으며, 중요도 기반 샘플링(Importance-Based Sampling)은 결과에 중대한 영향을 미치는 경험을 강조한다. 이러한 전략을 결합하면 모든 운영 궤적(Operational Trajectory)을 완전히 저장하지 않고도 지식 유지(Retention)를 개선할 수 있다.

정규화 방법(Regularization Method)은 중요한 모델 매개변수(Model Parameter)의 변화를 제한하여 이전 지식을 보호하려고 한다. 매개변수 중요도(Parameter Importance)를 기반으로 하는 기법은 이전에 획득한 능력(Previously Acquired Capability)을 손상시킬 수 있는 업데이트(Update)를 억제할 수 있다. 이러한 방법은 간섭(Interference)을 줄일 수 있지만 복잡한 물리적 작업(Physical Task) 전반에서 매개변수 중요도를 정확하게 추정하기는 어렵다. 공유 신경망 표현(Shared Neural Representation)에는 작업별로 명확하게 분리할 수 없는 지식이 포함될 수도 있다.

아키텍처 기반 접근법(Architectural Approach)은 모델 구성 요소(Model Component)를 분리하거나 확장함으로써 망각 문제를 해결한다. 새로운 작업에는 특화된 모듈(Specialized Module), 어댑터(Adapter), 매개변수 부분집합(Parameter Subset)을 할당하면서 기존 능력은 보호할 수 있다. 모듈형 정책(Modular Policy)은 적응 과정에서 신뢰할 수 있는 내비게이션(Navigation)이나 조작 기술(Manipulation Skill)을 보존할 수 있다. 그러나 지속적인 아키텍처 확장(Architectural Growth)은 메모리 요구량(Memory Requirement), 계산 비용(Computational Cost), 통합 복잡성(Integration Complexity)을 증가시켜 지식 유지와 확장성(Scalability) 사이의 절충 관계(Tradeoff)를 발생시킨다.

지식 증류(Knowledge Distillation)는 학습된 행동(Learned Behavior)을 보존하기 위한 또 다른 메커니즘을 제공한다. 이전에 검증된 모델(Previously Validated Model)은 새로운 모델이 추가 작업을 학습하는 동안 참조 예측(Reference Prediction)이나 행동 분포(Action Distribution)를 제공할 수 있다. 이는 모든 원본 훈련 사례(Original Training Example)를 필요로 하지 않으면서 행동의 연속성(Behavioral Continuity)을 유지하도록 유도한다. 그러나 지식 증류는 이전 모델의 오류(Model Error)를 보존할 수 있으며, 사용 가능한 전이 데이터(Transfer Data)에 충분히 표현되지 않은 능력을 유지하지 못할 수도 있다.

지식 축적(Knowledge Accumulation)은 단순히 성능 저하(Performance Degradation)를 방지하는 것 이상을 요구한다. 평생 학습 로봇(Lifelong Learning Robot)은 경험을 재사용 가능한 개념(Reusable Concept), 물리적 원리(Physical Principle), 작업 전략(Task Strategy), 실행 가능한 기술(Executable Skill)로 조직해야 한다. 개별 관측(Individual Observation)은 객체 특성(Object Property), 접촉 동역학(Contact Dynamics), 공간적 관계(Spatial Relationship), 행동 결과(Action Consequence)에 관한 일반적인 지식에 기여할 때 가치가 높아진다. 목표는 고립된 행동(Isolated Behavior)을 반복적으로 재학습하는 것이 아니라 누적적 능력(Cumulative Competence)을 확보하는 것이다.

구조화된 기억 아키텍처(Structured Memory Architecture)는 여러 수준에서 지식 축적을 지원할 수 있다. 일화 기억(Episodic Memory)은 구체적인 상호작용과 그 결과를 보존하고, 의미 기억(Semantic Memory)은 환경에 관한 일반화된 사실(Generalized Fact)을 표현하며, 절차 기억(Procedural Memory)은 재사용 가능한 기술을 저장한다. 이러한 기억 형태는 학습된 신경망 표현(Learned Neural Representation)을 보완할 수 있다. 효과적인 시스템은 어떤 경험을 개별적으로 유지하고, 추상화(Abstraction)하여 통합하며, 중복 정보(Redundant Information)로 판단해 폐기할지 결정해야 한다.

기억 통합(Memory Consolidation)은 반복된 경험(Repeated Experience)을 보다 안정적인 지식(Stable Knowledge)으로 전환한다. 예를 들어 미끄러운 표면(Slippery Surface)을 여러 차례 경험하면 모든 사건을 개별적으로 암기하는 대신 접지력(Traction)에 대한 일반화된 이해(Generalized Understanding)를 형성할 수 있다. 기억 통합은 저장 효율성(Storage Efficiency)과 환경 간 전이(Transfer Across Environments)를 향상시킬 수 있다. 그러나 성급한 일반화(Premature Generalization)는 중요한 예외(Exception)를 제거할 수 있으며, 지나치게 구체적인 기억(Overly Specific Memory)은 효율적인 추론(Reasoning)과 적응(Adaptation)을 방해할 수 있다.

지속적 월드 모델 학습(Continual World Model Learning)은 새로운 물리적 증거(Physical Evidence)가 이전 예측(Earlier Prediction)과 모순될 수 있으므로 추가적인 과제를 제기한다. 로봇은 익숙해 보이는 객체가 예상과 다른 질량(Mass), 마찰(Friction), 순응성(Compliance)을 가지고 있음을 발견할 수 있다. 모델 업데이트(Model Update)는 다른 객체에 관한 유효한 지식(Valid Knowledge)을 손상시키지 않으면서 예측을 개선해야 한다. 맥락 의존적 표현(Context-Dependent Representation)과 불확실성 인식 업데이트(Uncertainty-Aware Update)는 실제 예외(Genuine Exception)를 물리 법칙(Physical Law)의 보다 광범위한 변화와 구별하는 데 도움이 될 수 있다.

작업 간섭(Task Interference)은 학습 목표(Learning Objective)가 공유 모델 용량(Shared Model Capacity)을 두고 경쟁할 때 발생한다. 정밀한 접촉 제어(Precise Contact Control)를 요구하는 기술은 빠른 움직임(Rapid Movement)에 최적화된 정책과 충돌할 수 있으며, 서로 다른 환경은 양립할 수 없는 행동(Incompatible Behavior)을 보상할 수 있다. 다중 작업 최적화(Multi-Task Optimization)와 그래디언트 충돌 완화(Gradient Conflict Mitigation)는 해로운 간섭(Harmful Interference)을 줄일 수 있다. 그러나 계산 자원(Computational Resource)과 모델 용량(Model Capacity)이 제한된 상황에서 계속 확장되는 작업 집합(Task Collection)의 성능을 유지하는 것은 여전히 어렵다.

긍정적 전이(Positive Transfer)는 평생 학습(Lifelong Learning)에서 얻을 수 있는 상호 보완적인 기회이다. 작업들이 물리적 구조(Physical Structure)나 인과 관계(Causal Relationship)를 공유할 때 이전에 획득한 지식은 새로운 기술 개발(New Skill Development)을 가속할 수 있다. 용기를 파지한 경험은 익숙하지 않은 포장물을 다루는 데 도움이 될 수 있으며, 내비게이션 지식(Navigation Knowledge)은 유사한 시설(Facility) 사이에서 전이될 수 있다. 신뢰할 수 있는 지식 축적을 위해서는 공유 지식(Shared Knowledge)이 언제 적용 가능한지, 부적절한 전이(Inappropriate Transfer)가 언제 오류를 유발할 수 있는지 인식해야 한다.

망각은 신경망 훈련(Neural Training)뿐만 아니라 센싱 하드웨어(Sensing Hardware), 보정(Calibration), 행동 인터페이스(Action Interface)의 변화로도 발생할 수 있다. 카메라(Camera)를 교체하거나, 그리퍼(Gripper)를 수정하거나, 액추에이터 제어(Actuator Control)를 업데이트하면 기존 정책(Existing Policy)에 포함된 가정이 더 이상 유효하지 않을 수 있다. 따라서 지식 보존 시스템(Knowledge-Preservation System)은 모델 망각(Model Forgetting)과 하드웨어로 인한 성능 변화(Hardware-Induced Performance Change)를 구분해야 한다. 신체 구조(Embodiment)와 보정 이력(Calibration History)을 명시적으로 표현하면 문제 진단(Diagnosis)과 복구(Recovery)를 지원할 수 있다.

지속 학습 시스템(Continual Learning System)은 제한된 저장 공간(Storage), 에너지(Energy), 계산 자원(Computational Resource)을 고려해야 한다. 모든 경험을 보존하고 대규모 모델(Large Model)을 반복적으로 재훈련하는 것은 많은 배포 로봇(Deployed Robot)에서 비현실적이다. 기억 압축(Memory Compression), 선택적 경험 재생(Selective Replay), 매개변수 효율적 적응(Parameter-Efficient Adaptation), 계층적 기술 저장(Hierarchical Skill Storage)은 잠재적인 해결책을 제공한다. 이러한 방법의 효과는 계산, 통신(Communication), 추가적인 로봇 상호작용(Robot Interaction)에 필요한 물리적 비용(Physical Cost)을 기준으로 평가해야 한다.

플릿 규모 지식 축적(Fleet-Scale Knowledge Accumulation)은 여러 로봇이 공유 경험 저장소(Shared Experience Repository)에 기여하도록 할 수 있다. 분산 시스템(Distributed System)은 서로 다른 장소에서 수집한 드문 실패 사례(Rare Failure Case), 환경에 관한 새로운 발견(Environmental Discovery), 개선된 작업 전략(Improved Task Strategy)을 결합할 수 있다. 그러나 이질적인 하드웨어(Heterogeneous Hardware)와 운영 조건(Operating Condition)은 지식 통합(Knowledge Integration)을 복잡하게 만든다. 공유 업데이트(Shared Update)는 특정 장소에서 발생한 오류(Localized Error)가 다른 로봇의 성능을 저하시키지 않도록 검증해야 한다.

안전성(Safety)은 다른 지식이 변화하더라도 특정 능력을 반드시 보존해야 한다는 엄격한 요구사항을 부과한다. 충돌 회피(Collision Avoidance), 비상 정지(Emergency Stopping), 안정성 복구(Stability Recovery), 힘 제한(Force Limitation)은 지속적으로 업데이트되는 정책(Continually Updated Policy)에 전적으로 의존해서는 안 된다. 독립적인 안전 메커니즘(Independent Safety Mechanism)과 보호된 제어 기능(Protected Control Function)은 망각의 결과를 완화할 수 있다. 새로운 모델 버전(Model Version)은 이전에 검증된 운영 행동(Validated Operational Behavior)을 대체하기 전에 회귀 시험(Regression Testing)을 거쳐야 한다.

평가(Evaluation)는 지식 유지(Knowledge Retention)와 누적 학습 효율성(Cumulative Learning Efficiency)을 모두 측정해야 한다. 유용한 지표(Metric)에는 이전 작업 성능(Previous Task Performance), 적응 속도(Adaptation Speed), 역방향 전이(Backward Transfer), 순방향 전이(Forward Transfer), 메모리 사용량(Memory Consumption), 안전 위반(Safety Violation)이 포함된다. 장기간 벤치마크(Long-Duration Benchmark)는 이전 훈련 데이터(Earlier Training Data)에 제한 없이 접근할 수 없는 조건에서 로봇을 연속적인 작업(Sequential Task)과 변화하는 환경에 노출해야 한다. 시험은 실제로 축적된 능력(Genuine Accumulated Competence)과 벤치마크 시퀀스(Benchmark Sequence)의 암기를 구분해야 한다.

주요 미해결 질문(Open Question)은 로봇이 어떤 경험을 영구적으로 보존(Permanent Retention)할 가치가 있는지 어떻게 결정해야 하는가에 관한 것이다. 일상적인 운영(Routine Operation)에서는 중요하지 않아 보이는 정보가 드문 조건(Rare Condition)이 다시 발생할 때 결정적으로 중요해질 수 있다. 반대로 지나친 보존(Excessive Preservation)은 적응을 방해하고 사용 가능한 메모리(Available Memory)를 초과하게 만들 수 있다. 지능형 기억 관리(Intelligent Memory Management)를 위해서는 관련성(Relevance), 불확실성(Uncertainty), 미래 효용(Future Utility), 특정 지식을 잃었을 때의 결과(Consequence)를 추정해야 한다.

궁극적으로 치명적 망각(Catastrophic Forgetting)을 극복하는 것은 평생 피지컬 인공지능(Lifelong Physical AI)에 필요하지만 충분하지는 않다. 로봇은 신뢰할 수 있는 기술(Reliable Skill)을 보존하고, 경험을 전이 가능한 추상화(Transferable Abstraction)로 통합하며, 상충하는 지식(Conflicting Knowledge)을 해결하고, 지속적인 상호작용(Sustained Interaction)을 통해 능력을 확장해야 한다. 범용 물리 지능(General Physical Intelligence)을 향한 발전은 순차 학습(Sequential Learning)을 반복적인 지식 대체(Repeated Replacement) 과정에서 안정적이고 누적적이며 안전하게 재사용할 수 있는 지식(Stable, Cumulative, and Safely Reusable Knowledge)을 형성하는 과정으로 전환하는 데 달려 있다.

## 07.11. Physical Reasoning and Deliberation

![](images/image11.png){width="7.268055555555556in" height="7.268055555555556in"}

물리적 추론(Physical Reasoning)과 숙고(Deliberation)는 자율 시스템(Autonomous System)이 행동을 선택하기 전에 물리적 상황(Physical Situation)을 이해해야 한다는 점에서 피지컬 인공지능(Physical AI)의 핵심 연구 과제이다. 순수한 디지털 추론(Digital Reasoning)과 달리 로봇의 의사결정(Robotic Decision-Making)은 기하학(Geometry), 운동(Motion), 접촉(Contact), 힘(Force), 불확실성(Uncertainty), 되돌릴 수 없는 결과(Irreversible Consequence)를 수반한다. 유능한 로봇은 자신의 행동이 주변 환경을 어떻게 변화시킬지 예측하면서 추상적인 목표(Abstract Goal)를 물리적 제약(Physical Constraint)과 연결해야 한다.

물리적 추론(Physical Reasoning)은 어떤 행동이 가능한지 판단하기 위해 객체(Object), 재료(Material), 공간적 관계(Spatial Relationship), 동적 상호작용(Dynamic Interaction)을 해석하는 과정이다. 무거운 용기(Heavy Container)를 이동시키는 로봇은 질량(Mass), 마찰(Friction), 이동 가능한 여유 공간(Available Clearance), 잠재적인 불안정성(Potential Instability)을 고려해야 한다. 이러한 특성은 시각적 외관(Visual Appearance)만으로 항상 추론할 수 있는 것은 아니다. 따라서 신뢰할 수 있는 추론(Reliable Reasoning)을 위해서는 감각 관측(Sensory Observation), 학습된 물리적 지식(Learned Physical Knowledge), 행동 결과 예측(Action Outcome Prediction)을 결합해야 한다.

숙고(Deliberation)는 실행 전에 대안 행동(Alternative Action)을 평가함으로써 즉각적인 의사결정(Immediate Decision-Making)을 확장한다. 로봇은 현재 관측(Current Observation)으로부터 직접 반응을 선택하는 대신 후보 행동(Candidate Behavior)을 시뮬레이션하고, 예상 결과(Expected Outcome)를 비교하며, 적절한 전략(Suitable Strategy)을 선택할 수 있다. 이러한 과정은 행동 비용(Action Cost)이 높거나 되돌리기 어려운 경우 특히 중요하다. 그러나 광범위한 숙고는 계산 지연(Computational Latency)을 발생시키므로 운영 마감시간(Operational Deadline)과 균형을 이루어야 한다.

핵심 과제는 기호적 추론(Symbolic Reasoning)과 연속적인 물리적 예측(Continuous Physical Prediction)을 모두 지원하는 표현(Representation)을 구축하는 것이다. 기호적 설명(Symbolic Description)은 객체, 목표, 제약, 작업 관계(Task Relationship)를 포착하고, 연속 모델(Continuous Model)은 위치(Position), 속도(Velocity), 힘, 접촉 동역학(Contact Dynamics)을 표현한다. 어느 한 표현만으로 모든 상황을 충분히 설명할 수는 없다. 이들을 통합하면 로봇이 저수준 물리적 실행 가능성(Low-Level Physical Feasibility)을 준수하면서 고수준 의도(High-Level Intention)에 관해 추론할 수 있을 것이다.

월드 모델(World Model)은 후보 행동에 따라 환경이 어떻게 변화하는지 예측함으로써 물리적 숙고(Physical Deliberation)를 위한 계산적 기반(Computational Foundation)을 제공한다. 로봇은 객체를 밀었을 때 충분한 여유 공간이 확보되는지, 다른 방향에서 파지하면 안정성(Stability)이 향상되는지 추정할 수 있다. 이러한 예측은 모든 대안을 실제로 시험하지 않고도 계획(Planning)을 지원한다. 그 유용성은 예측 정확도(Prediction Accuracy)와 모델 불확실성(Model Uncertainty)에 대한 인식에 달려 있다.

인과적 추론(Causal Reasoning)은 로봇이 상관관계(Correlation)와 물리적 결과를 결정하는 메커니즘(Mechanism)을 구분해야 하므로 필수적이다. 접촉 후 객체가 움직이는 것을 관측했다고 해서 어떤 힘이나 제약이 움직임을 유발했는지 확인되는 것은 아니다. 인과 구조(Causal Structure)를 이해하면 로봇이 효과적인 개입(Intervention)을 선택하고 익숙하지 않은 상황에 적응하는 데 도움이 된다. 그러나 관측이 불완전하고 통제된 실험(Controlled Experiment)의 비용이 높은 상황에서는 이러한 관계를 학습하기 어렵다.

반사실적 추론(Counterfactual Reasoning)은 로봇이 다른 행동을 선택했을 때 어떤 일이 발생할 수 있는지 고려하도록 한다. 깨지기 쉬운 객체(Fragile Object)를 들어 올리기 전에 시스템은 서로 다른 파지 위치(Grasp Location), 접촉력(Contact Force), 운동 궤적(Motion Trajectory)을 비교할 수 있다. 반사실적 예측(Counterfactual Prediction)은 장비를 불필요한 위험에 노출시키지 않으면서 잠재적인 실패(Potential Failure)를 발견할 수 있다. 그러나 신뢰성은 물리적 제약과 불확실한 상호작용을 정확하게 표현하는 모델에 달려 있다.

장기 숙고(Long-Horizon Deliberation)는 결과가 훨씬 나중에 나타날 수 있는 행동 시퀀스(Action Sequence) 전반에 걸친 추론을 요구한다. 조립 로봇(Assembly Robot)은 체결 작업(Fastening Operation)을 완료하기 전에 부품(Component)의 위치를 다시 조정해야 할 수 있으며, 모바일 매니퓰레이터(Mobile Manipulator)는 목적지에 도달하기 위해 장애물(Obstacle)을 재배치해야 할 수 있다. 따라서 국소적 행동(Local Action)은 미래 목표(Future Goal)와의 관계 속에서 평가되어야 한다. 예측된 중간 상태(Intermediate State)의 오류는 누적되어 다른 측면에서는 합리적인 계획을 무너뜨릴 수 있다.

계층적 추론(Hierarchical Reasoning)은 전략적 목표(Strategic Objective)와 세부적인 운동 실행(Motor Execution)을 분리하여 복잡성을 줄일 수 있다. 고수준 계획(High-Level Planning)은 작업 순서(Task Order)와 자원 할당(Resource Allocation)을 결정하고, 하위 수준(Lower Level)은 운동 궤적과 접촉 전략(Contact Strategy)을 선택한다. 이러한 분해(Decomposition)는 모든 모터 명령(Motor Command)을 동시에 평가하지 않고도 장기간의 작업을 추론할 수 있도록 한다. 그러나 예상하지 못한 물리적 사건(Physical Event)이 고수준 가정(High-Level Assumption)을 무효화할 때 계층 간 조정(Coordination)은 여전히 어려운 과제이다.

추론 시점 연산(Test-Time Computation)은 어려운 결정에 추가적인 추론 노력(Reasoning Effort)을 할당하는 메커니즘을 제공한다. 단순한 행동에는 최소한의 숙고가 필요할 수 있지만, 불확실한 조작(Uncertain Manipulation)이나 위험한 내비게이션(Hazardous Navigation)에는 여러 후보 계획(Candidate Plan)을 평가하는 것이 타당할 수 있다. 적응형 연산(Adaptive Computation)은 가장 큰 이점을 제공하는 곳에 자원을 집중함으로써 효율성을 높일 수 있다. 아직 해결되지 않은 질문은 계산 자원(Computational Resource)을 투입하기 전에 추가 추론의 가치(Value of Further Reasoning)를 어떻게 추정할 것인가이다.

물리적 숙고(Physical Deliberation)는 로봇이 추론하는 동안에도 환경이 계속 변화하므로 엄격한 시간 제약(Timing Constraint) 아래에서 작동해야 한다. 내비게이션 시스템(Navigation System)은 접근하는 장애물(Approaching Obstacle)을 무한정 분석할 수 없으며, 매니퓰레이터(Manipulator)는 불안정한 접촉(Unstable Contact) 상황에서 필요한 안정화(Stabilization)를 지연시킬 수 없다. 효과적인 아키텍처(Architecture)는 빠른 반응형 제어(Fast Reactive Control)와 상대적으로 느린 예측 계획(Predictive Planning)을 결합할 수 있다. 핵심 과제는 적시에 안전 대응(Timely Safety Response)을 보장하면서 두 과정 사이의 일관성(Consistency)을 유지하는 것이다.

불확실성 인식 추론(Uncertainty-Aware Reasoning)은 물리적 예측이 거의 정확하게 일치하지 않기 때문에 필요하다. 센서 잡음(Sensor Noise), 알려지지 않은 재료 특성(Unknown Material Property), 불완전한 보정(Imperfect Calibration), 예측하기 어려운 인간 행동(Unpredictable Human Behavior)은 여러 가지 가능한 결과(Plausible Outcome)를 발생시킬 수 있다. 로봇은 단일한 예측 미래(Predicted Future)에만 의존하지 않고 불확실성 범위(Uncertainty Range) 전반에서 계획을 평가해야 한다. 강건한 의사결정(Robust Decision)은 위험하거나 복구 불가능한 결과의 발생 확률을 줄이기 위해 명목상 효율성(Nominal Efficiency)을 일부 희생할 수 있다.

능동 인식(Active Perception)은 추론(Reasoning)과 정보 수집(Information Gathering)을 연결한다. 불확실성 때문에 신뢰할 수 있는 결정을 내리기 어려울 때 로봇은 관측 시점(Viewpoint)을 변경하거나, 객체를 검사하거나, 작은 탐색적 상호작용(Exploratory Interaction)을 수행할 수 있다. 이러한 행동은 숨겨진 기하학적 구조(Hidden Geometry), 접촉 조건(Contact Condition), 재료 특성(Material Characteristic)을 드러낼 수 있다. 숙고는 예상 정보 이득(Expected Information Gain)이 추가 센싱(Additional Sensing)에 필요한 시간, 에너지, 물리적 위험(Physical Risk)을 정당화하는지 판단해야 한다.

상식적 물리 지식(Commonsense Physical Knowledge)은 지지(Support), 포함 관계(Containment), 안정성(Stability), 객체 상호작용(Object Interaction)에 관한 유용한 예측을 제공한다. 로봇은 지지되지 않는 객체(Unsupported Object)가 떨어질 수 있고, 막힌 문(Blocked Door)은 자유롭게 열릴 수 없으며, 쌓인 재료(Stacked Material)는 지지 상태가 변화하면 무너질 수 있음을 인식해야 한다. 이러한 지식은 상세한 시뮬레이션(Detailed Simulation) 이전에 계획을 안내할 수 있다. 그러나 광범위한 물리적 예측(Physical Expectation)을 정밀하고 맥락 의존적인 제어 결정(Context-Dependent Control Decision)으로 전환하는 것은 여전히 미해결 과제이다.

언어 기반 추론(Language-Guided Reasoning)은 인간의 의도(Human Intention)를 실행 가능한 물리적 계획(Executable Physical Plan)과 연결할 수 있다. 작업 공간 정리(Clearing a Workspace)나 느슨한 부품 고정(Securing a Loose Component)과 같은 지시는 목표, 객체, 제약, 허용 가능한 결과(Acceptable Outcome)에 대한 해석을 요구한다. 시각-언어-행동 모델(Vision-Language-Action Model)은 의미적 설명(Semantic Description)을 후보 행동(Candidate Behavior)으로 변환하는 데 도움이 될 수 있다. 그러나 언어적 개연성(Linguistic Plausibility)이 물리적 실행 가능성(Physical Feasibility)을 보장하지는 않으므로 물리적 기반 검증(Grounded Verification)이 필수적이다.

도구 사용(Tool Use)은 도구가 로봇 행동과 환경에 미치는 효과 사이의 관계를 변화시키므로 추가적인 추론 능력을 요구한다. 지렛대(Lever), 그리퍼(Gripper), 청소 도구(Cleaning Implement)를 사용하는 로봇은 접촉 기하학(Contact Geometry), 기계적 이점(Mechanical Advantage), 작업별 제약(Task-Specific Constraint)을 고려해야 한다. 도구 사용의 일반화(Generalization)는 외관을 암기하는 것이 아니라 기능적 특성(Functional Property)을 이해하는 것을 요구한다. 이는 도구나 작업 조건(Working Condition)이 훈련 사례(Training Example)와 다를 때 여전히 어려운 과제이다.

다중 로봇 숙고(Multi-Robot Deliberation)는 물리적 추론을 여러 자율 에이전트(Autonomous Agent) 사이의 상호작용으로 확장한다. 작업 공간(Workspace)을 공유하는 로봇은 서로의 궤적(Trajectory), 작업 의존성(Task Dependency), 자원 요구사항(Resource Requirement)을 예측해야 한다. 협조적 계획(Coordinated Planning)은 효율성을 높이고 간섭(Interference)을 방지할 수 있지만, 불확실성과 통신 요구사항(Communication Requirement)도 증가시킨다. 분산 추론(Distributed Reasoning)은 에이전트가 불완전한 정보(Incomplete Information)를 보유하거나 일시적으로 연결이 끊어지는 상황에서도 신뢰성을 유지해야 한다.

경험으로부터 숙고를 학습하는 방법(Learning to Deliberate from Experience)은 비용이 높은 전수 탐색(Exhaustive Search)에 대한 의존도를 줄일 수 있다. 로봇은 유망한 행동(Promising Action)을 식별하고, 예상되는 실패(Likely Failure)를 인식하며, 정보 가치가 높은 시뮬레이션(Informative Simulation)에 우선순위를 부여하는 휴리스틱(Heuristic)을 습득할 수 있다. 성공적인 전략(Successful Strategy)은 재사용 가능한 계획 기술(Reusable Planning Skill)이 될 수 있다. 그러나 학습된 추론 지름길(Learned Reasoning Shortcut)은 훈련 편향(Training Bias)을 재현할 수 있으므로 익숙하지 않거나 위험도가 높은 상황에서는 명시적인 물리적 검증(Explicit Physical Verification)이 여전히 필요할 수 있다.

안전 제약(Safety Constraint)은 최종 점검(Final Check)에만 적용되는 것이 아니라 숙고 과정 자체를 형성해야 한다. 후보 계획(Candidate Plan)은 충돌 한계(Collision Limit), 힘 임계값(Force Threshold), 인간과의 근접성(Human Proximity), 장비 안정성(Equipment Stability), 비상 복구 선택지(Emergency Recovery Option)를 고려해야 한다. 이론적으로 효율적인 행동이라도 실패 결과(Failure Consequence)가 심각하다면 허용될 수 없다. 안전성을 추론에 통합하려면 예상 성능(Expected Performance)과 현실적으로 발생 가능한 위험 결과(Credible Hazardous Outcome)를 모두 표현하는 모델이 필요하다.

물리적 추론의 평가(Evaluation of Physical Reasoning)는 로봇이 최종적으로 작업을 완료했는지만 측정해서는 안 된다. 벤치마크(Benchmark)는 인과적 이해(Causal Understanding), 반사실적 정확도(Counterfactual Accuracy), 계획 효율성(Planning Efficiency), 강건성(Robustness), 익숙하지 않은 물리적 조건(Unfamiliar Physical Condition)에 대한 적응을 검토해야 한다. 통제된 실험(Controlled Experiment)은 시스템이 행동의 성공이나 실패 원인을 이해하는지 시험할 수 있다. 시뮬레이션 기반 추론 성능(Simulated Reasoning Performance)이 물리적 상호작용(Physical Interaction)으로 신뢰성 있게 전이되지 않을 수 있으므로 실제 세계 평가(Real-World Evaluation)는 필수적이다.

주요 연구 질문(Research Question)은 서로 다른 유형의 로봇 행동(Robotic Behavior)에 얼마나 많은 명시적 추론(Explicit Reasoning)이 필요한가에 관한 것이다. 일부 작업은 학습된 반응형 정책(Learned Reactive Policy)을 통해 효율적으로 해결할 수 있지만, 다른 작업에는 구조화된 탐색(Structured Search), 시뮬레이션(Simulation), 기호적 계획(Symbolic Planning)이 필요하다. 범용 피지컬 인공지능 시스템(General Physical AI System)은 각 상황에 적합한 추론 메커니즘(Reasoning Mechanism)을 결정해야 한다. 이러한 유연성(Flexibility)은 모든 행동에 계산 비용이 높은 숙고(Computationally Expensive Deliberation)를 적용하는 것보다 더 가치 있을 수 있다.

또 다른 미해결 과제(Unresolved Challenge)는 추론을 지속 학습(Continual Learning) 및 영속적 기억(Persistent Memory)과 통합하는 것이다. 물리적 경험(Physical Experience)은 인과 모델(Causal Model)을 정교화하고, 계획 휴리스틱(Planning Heuristic)을 개선하며, 이전에 알려지지 않은 제약(Previously Unknown Constraint)을 발견하는 데 기여해야 한다. 동시에 잘못된 결론(Incorrect Conclusion)이 미래 행동에 영향을 미치는 영구적인 가정(Permanent Assumption)으로 굳어져서는 안 된다. 신뢰할 수 있는 지식 수정(Reliable Knowledge Revision)을 위해서는 증거 추적(Evidence Tracking), 불확실성 추정(Uncertainty Estimation), 다양한 물리적 맥락(Physical Context)에 걸친 검증(Validation)이 필요하다.

궁극적으로 물리적 추론(Physical Reasoning)과 숙고(Deliberation)는 로봇 행동을 즉각적인 자극-반응 매핑(Stimulus-Response Mapping)에서 물리적 세계(Physical World)와의 정보에 기반한 목표 지향적 상호작용(Informed, Goal-Directed Interaction)으로 전환하는 것을 목표로 한다. 발전은 물리적 기반 표현(Grounded Representation), 예측 월드 모델(Predictive World Model), 인과적 이해(Causal Understanding), 적응형 연산(Adaptive Computation), 안전 인식 계획(Safety-Aware Planning)에 달려 있다. 이러한 능력은 실제 세계 제약(Real-World Constraint) 아래에서 신뢰성 있게 행동하면서 익숙하지 않은 문제(Unfamiliar Problem)를 해결해야 하는 피지컬 인공지능 시스템에 필수적이다.

## 07.12. Uncertainty and Reliable Decision Making

![](images/image12.png){width="7.268055555555556in" height="7.268055555555556in"}

불확실성(Uncertainty)과 신뢰할 수 있는 의사결정(Reliable Decision-Making)은 자율 로봇(Autonomous Robot)이 불완전한 관측(Incomplete Observation), 부정확한 모델(Imperfect Model), 예측하기 어려운 환경(Unpredictable Environment)에서도 행동해야 한다는 점에서 피지컬 인공지능(Physical AI)의 핵심 과제이다. 디지털 시스템(Digital System)과 달리 물리적 행동(Physical Action)은 장비, 인프라, 인간의 안전(Human Safety)에 관련된 되돌릴 수 없는 결과(Irreversible Consequence)를 초래할 수 있다. 따라서 신뢰할 수 있는 자율성(Reliable Autonomy)을 위해서는 로봇이 불확실성을 인식하고, 그 결과를 추정하며, 변화하는 조건에서도 허용 가능한 행동을 선택해야 한다.

불확실성(Uncertainty)은 로봇의 인식(Perception)과 제어(Control) 전반에 걸쳐 다양한 원인에서 발생한다. 센서(Sensor)는 측정 잡음(Measurement Noise), 가림(Occlusion), 보정 오류(Calibration Error)를 발생시키며, 월드 모델(World Model)은 복잡한 물리적 상호작용(Physical Interaction)을 근사적으로 표현한다. 알려지지 않은 객체 특성(Unknown Object Property)과 예상하지 못한 인간 행동(Unexpected Human Behavior)은 추가적인 변동성(Variability)을 발생시킨다. 로봇은 적절한 대응을 결정하기 위해 지식 부족(Limited Knowledge)으로 인한 불확실성과 환경 자체에 내재된 변동성을 구분해야 한다.

우연적 불확실성(Aleatoric Uncertainty)은 단순히 더 많은 정보를 수집하는 것만으로 제거할 수 없는 무작위성(Randomness)이나 변동성(Variability)을 의미한다. 대표적인 사례에는 센서 잡음(Sensor Noise), 예측하기 어려운 표면 상호작용(Surface Interaction), 확률적 환경 교란(Stochastic Environmental Disturbance)이 포함된다. 인식론적 불확실성(Epistemic Uncertainty)은 모델, 객체, 운영 조건(Operating Condition)에 관한 지식이 부족한 상태를 나타낸다. 이러한 구분이 중요한 이유는 추가 관측(Additional Observation)이 인식론적 불확실성을 줄일 수 있는 반면, 우연적 불확실성은 강건한 의사결정 정책(Robust Decision Policy)을 요구하는 경우가 많기 때문이다.

불확실성 추정(Uncertainty Estimation)은 인식 결과(Perception Output)에 신뢰도 점수(Confidence Score)를 부여하는 수준을 넘어야 한다. 로봇은 객체를 정확하게 인식하면서도 그 객체의 질량(Mass), 마찰(Friction), 안정성(Stability), 접촉 반응(Contact Response)에 대해서는 불확실할 수 있다. 신뢰할 수 있는 의사결정에는 기하학(Geometry), 동역학(Dynamics), 작업 결과(Task Outcome), 안전 제약(Safety Constraint)을 포괄하는 불확실성 표현(Uncertainty Representation)이 필요하다. 이러한 추정값은 인식, 계획(Planning), 제어 모듈(Control Module) 사이에서 정보가 전달될 때에도 의미를 유지해야 한다.

확률적 상태 추정(Probabilistic State Estimation)은 불완전한 관측 아래에서 추론하기 위한 기반을 제공한다. 베이지안 필터링(Bayesian Filtering) 방법은 센서 측정값(Sensor Measurement)과 운동 모델(Motion Model)을 결합하여 로봇과 환경의 가능한 상태(Possible State)를 추정한다. 칼만 필터(Kalman Filter)와 파티클 필터(Particle Filter)는 이러한 신념 상태(Belief State)를 유지하는 서로 다른 접근법을 보여준다. 그러나 복잡한 접촉 동역학(Contact Dynamics)과 변화하는 환경은 모델링 가정(Modeling Assumption)을 위반할 수 있으며, 그 결과 추정된 신뢰도(Estimated Confidence)가 실제와 다르게 나타날 수 있다.

신념 상태 계획(Belief-State Planning)은 하나의 알려진 환경 구성(Environment Configuration)을 가정하는 대신 여러 가능한 환경 상태(Environment State)를 고려한다. 부분 관측 마르코프 의사결정 과정(Partially Observable Markov Decision Process, POMDP)은 불확실한 관측과 상태 전이(State Transition) 아래에서 행동을 선택하기 위한 형식적 프레임워크(Formal Framework)를 제공한다. 이러한 방법은 작업 진행(Task Progress)과 정보 수집(Information Gathering) 사이의 균형을 유지할 수 있다. 그러나 로봇이 연속적인 행동(Continuous Action)을 포함하는 고차원 공간(High-Dimensional Space)에서 작동할 때 계산 복잡성(Computational Complexity)은 여전히 주요 장애물이다.

예측 월드 모델(Predictive World Model)은 미래 물리적 상태(Future Physical State)에 관한 불확실성을 발생시킨다. 마찰, 접촉 기하학(Contact Geometry), 액추에이터 반응(Actuator Response)의 추정에서 발생한 작은 오류도 여러 행동 이후에는 상당히 다른 결과를 초래할 수 있다. 따라서 신뢰할 수 있는 계획(Reliable Planning)은 하나의 결정론적 예측(Deterministic Prediction)이 아니라 가능한 궤적(Possible Trajectory)의 확률 분포(Probability Distribution)를 고려해야 한다. 장기 예측 구간(Long Horizon)에서 유용한 불확실성 추정값을 유지하는 것은 예측 오류(Prediction Error)가 누적되고 상호작용할 수 있기 때문에 여전히 어렵다.

모델 앙상블(Model Ensemble)은 독립적으로 훈련된 모델들의 예측을 비교하여 불확실성을 추정할 수 있다. 모델 간 일치(Agreement)는 비교적 안정적인 예측을 나타낼 수 있으며, 불일치(Disagreement)는 익숙하지 않은 상황이나 불충분한 훈련 데이터 범위(Training Coverage)를 드러낼 수 있다. 그러나 앙상블 모델들은 체계적 오류(Systematic Error)를 공유할 수 있으며, 잘못된 일치 결과를 만들어낼 수도 있다. 신뢰할 수 있는 불확실성 평가(Uncertainty Assessment)를 위해서는 모델 간 합의(Model Consensus)를 정확성의 증거로 간주하는 대신 실제 결과(Real Outcome)에 대한 검증이 필요하다.

보정(Calibration)은 예측된 신뢰도(Predicted Confidence)가 관측된 신뢰성(Observed Reliability)에 부합하는지를 결정한다. 높은 신뢰도를 보고하는 로봇은 비교 가능한 조건에서 그에 상응하는 높은 빈도로 성공해야 한다. 잘못된 보정(Poor Calibration)은 위험한 과신(Overconfidence)이나 불필요하게 보수적인 행동(Conservative Behavior)을 유발할 수 있다. 훈련 과정에서 유효했던 신뢰도 추정값이 배포 이후에는 실패할 수 있으므로, 보정은 서로 다른 환경, 작업, 위험 수준(Risk Level) 전반에서 평가되어야 한다.

분포 변화(Distribution Shift)는 운영 조건(Operational Condition)이 훈련 데이터(Training Data)에 표현된 조건과 달라질 때 발생한다. 새로운 조명(New Lighting), 익숙하지 않은 재료(Unfamiliar Material), 변경된 공간 배치(Changed Layout), 성능이 저하된 센서(Degraded Sensor)는 학습된 가정(Learned Assumption)을 무효화할 수 있다. 분포 외 탐지(Out-of-Distribution Detection)는 비정상적인 관측(Unusual Observation)을 식별할 수 있지만, 새로운 상황을 인식하는 것만으로 그 위험성을 자동으로 판단할 수 있는 것은 아니다. 로봇에는 분포 변화를 작업 관련성(Task Relevance) 및 적절한 운영 대응(Operational Response)과 연결하는 메커니즘이 필요하다.

위험 민감형 의사결정(Risk-Sensitive Decision-Making)은 기대 작업 성능(Expected Task Performance)뿐만 아니라 불리한 결과(Unfavorable Outcome)의 영향도 평가한다. 평균 보상(Average Reward)이 비슷한 두 행동이라도 손상을 유발할 확률(Probability of Damage)은 크게 다를 수 있다. 신뢰할 수 있는 로봇은 대안을 비교할 때 실패 심각도(Failure Severity), 복구 비용(Recovery Cost), 불확실성을 고려해야 한다. 이는 안전 여유도(Safety Margin)가 상당히 높은 경우 더 느리거나 효율성이 낮은 행동을 선택하는 것을 정당화할 수 있다.

강건 최적화(Robust Optimization)는 모델 매개변수(Model Parameter)와 환경 조건(Environmental Condition)의 가능한 변화 전반에서 효과를 유지하는 의사결정을 추구한다. 조작 계획기(Manipulation Planner)는 불확실한 객체 질량(Object Mass)을 고려할 수 있으며, 이동 로봇(Mobile Robot)은 접지력(Traction)의 변화를 고려하여 경로를 계획할 수 있다. 보수적인 가정(Conservative Assumption)은 안전성을 향상시킬 수 있지만 생산성(Productivity)을 저하시킬 수도 있다. 핵심 과제는 유용한 행동을 불필요하게 불가능하게 만들지 않으면서 현실적으로 발생 가능한 조건을 포괄하는 불확실성 집합(Uncertainty Set)을 정의하는 것이다.

확률 제약 계획(Chance-Constrained Planning)은 선택된 위험을 확률적으로 제한할 수 있도록 한다. 예를 들어 궤적 계획기(Trajectory Planner)는 충돌 확률(Collision Probability)이 지정된 임계값(Threshold) 이하로 유지되도록 요구할 수 있다. 이러한 제약은 불확실성 추정값을 명시적인 운영 요구사항(Operational Requirement)과 연결한다. 그러나 그 보장 수준(Guarantee)은 확률 모델(Probability Model)의 타당성에 의존하며, 드물게 발생하는 위험 사건(Rare Hazardous Event)은 사용 가능한 훈련 데이터나 평가 데이터(Evaluation Data)에 충분히 표현되지 않을 수 있다.

조건부 위험가치(Conditional Value at Risk, CVaR)는 손실 분포(Loss Distribution)의 불리한 꼬리 영역(Tail)에 존재하는 심각한 결과를 강조하는 또 다른 관점을 제공한다. 로봇은 평균 성능만 최적화하는 대신 특히 피해가 큰 실패(Damaging Failure)의 결과를 줄이는 데 우선순위를 둘 수 있다. 이러한 접근법은 깨지기 쉬운 장비(Fragile Equipment)나 위험한 환경(Hazardous Environment)을 다루는 의사결정을 지원할 수 있다. 실제 효과는 드문 사건의 결과(Rare-Event Consequence)에 대해 신뢰할 수 있는 추정값을 확보할 수 있는지에 달려 있다.

능동 인식(Active Perception)은 로봇이 어려운 행동을 실행하기 전에 불확실성을 줄일 수 있도록 한다. 매니퓰레이터(Manipulator)는 다른 관측 시점(Viewpoint)에서 객체를 검사할 수 있으며, 이동 로봇은 더 신뢰할 수 있는 지형 측정(Terrain Measurement)을 확보하기 위해 속도를 줄일 수 있다. 이러한 정보 수집 행동(Information-Gathering Action)은 시간과 에너지를 소비하지만 비용이 큰 실수를 방지할 수 있다. 신뢰할 수 있는 의사결정은 추가 센싱(Additional Sensing)이 즉각적인 작업 실행(Immediate Task Execution)보다 언제 더 가치 있는지 추정해야 한다.

정보 가치(Value of Information)는 추가 관측(Additional Observation)이나 실험(Experiment)이 수행할 가치가 있는지 판단하기 위한 형식적 관점을 제공한다. 로봇은 정보 획득 비용(Acquisition Cost)을 정당화할 만큼 선호 행동(Preferred Action)을 변화시킬 가능성이 있을 때 정보를 수집해야 한다. 그러나 정보 수집 자체에도 물리적 위험(Physical Risk)이 수반될 수 있다. 따라서 안전한 탐색(Safe Exploration)은 유용한 불확실성 감소(Useful Uncertainty Reduction)와 위험한 조건에 대한 불필요한 노출(Unnecessary Exposure)을 구분해야 한다.

불확실성이 자율 운영 한계(Autonomous Operating Limit)를 초과할 때에는 인간의 개입(Human Involvement)이 여전히 중요하다. 로봇은 사용 가능한 증거(Available Evidence)가 신뢰할 수 있는 결정을 뒷받침하지 못하면 확인을 요청하거나, 제어권을 이전하거나, 작업을 중단할 수 있다. 효과적인 상위 단계 이관(Escalation)을 위해서는 의미 있는 불확실성 지표(Uncertainty Indicator)와 운영상 결과(Operational Consequence)에 대한 명확한 설명이 필요하다. 과도한 요청은 운영자(Operator)에게 부담을 줄 수 있으며, 개입이 지연되면 관리 가능한 문제가 위험한 상황으로 확대될 수 있다.

런타임 보증(Runtime Assurance)은 불확실한 학습 기반 의사결정(Learned Decision)에 대해 독립적인 보호 계층(Independent Protection Layer)을 제공할 수 있다. 모니터링 시스템(Monitoring System)은 예측 궤적(Predicted Trajectory)을 평가하고, 안전 경계(Safety Boundary)를 강제하거나, 신뢰도가 저하될 때 대체 제어기(Fallback Controller)를 활성화할 수 있다. 이러한 메커니즘은 주 학습 모델(Primary Learning Model)이 잘못된 경우에도 효과적으로 작동해야 한다. 그러나 신뢰할 수 있는 모니터(Dependable Monitor)를 설계하려면 센싱 정확도(Sensing Accuracy), 시스템 동역학(System Dynamics), 개입 시점(Intervention Timing)에 관한 명시적인 가정이 필요하다.

신뢰할 수 있는 의사결정(Reliable Decision-Making)은 불확실성을 충분히 줄일 수 없는 상황을 인식하는 능력도 요구한다. 일부 환경에는 숨겨진 위험(Hidden Hazard), 예측하기 어려운 에이전트(Unpredictable Agent), 사용 가능한 모델링 능력(Modeling Capability)을 초과하는 물리적 상호작용이 존재한다. 이러한 상황에서는 정지(Stopping), 후퇴(Retreating), 제한된 운영 모드(Restricted Operating Mode)의 선택이 가장 적절한 대응일 수 있다. 자율적 역량(Autonomous Competence)에는 행동을 계속하는 것이 정당화되지 않는 시점을 판단하는 능력도 포함된다.

다중 로봇 시스템(Multi-Robot System)은 통신 지연(Communication Delay), 불완전한 공유 관측(Incomplete Shared Observation), 예측하기 어려운 협조 결과(Coordination Outcome)로 인해 추가적인 불확실성을 발생시킨다. 한 로봇은 다른 로봇의 위치(Location)나 의도된 궤적(Intended Trajectory)에 관한 오래된 정보(Outdated Information)를 사용하여 계획할 수 있다. 분산 의사결정(Distributed Decision-Making)은 이러한 불일치를 고려하면서 안전한 분리 거리(Safe Separation)와 작업 협조(Task Coordination)를 유지해야 한다. 공유 신뢰도 추정값(Shared Confidence Estimate)은 도움이 될 수 있지만, 로봇별 국소 정보 품질(Local Information Quality)의 차이를 반영해야 한다.

불확실성 인식 피지컬 인공지능(Uncertainty-Aware Physical AI)의 평가는 일반적인 작업 성공(Task Success)과 함께 보정(Calibration), 강건성(Robustness), 위험 노출(Risk Exposure), 복구 행동(Recovery Behavior)을 측정해야 한다. 벤치마크(Benchmark)에는 익숙하지 않은 조건(Unfamiliar Condition), 센서 성능 저하(Sensor Degradation), 모호한 관측(Ambiguous Observation), 드문 위험 사건(Rare Hazardous Event)이 포함되어야 한다. 시험은 신뢰도가 낮아질 때 로봇이 적절하게 신중해지는지 확인해야 한다. 신뢰할 수 있는 불확실성 처리(Uncertainty Handling)는 신뢰도 예측만이 아니라 실제 물리적 결과(Physical Outcome)를 통해 입증되어야 한다.

주요 미해결 질문(Unresolved Question)은 통합 로봇 아키텍처(Integrated Robotic Architecture) 전반에서 불확실성이 어떻게 전파되어야 하는가에 관한 것이다. 인식 오류(Perception Error)는 월드 모델(World Model), 계획 결정(Planning Decision), 제어 행동(Control Action)에 영향을 미치며, 이러한 관계는 종종 비선형적(Nonlinear)이다. 독립적인 신뢰도 추정(Independent Confidence Estimate)은 모듈 간 상관된 오류(Correlated Error)를 충분히 포착하지 못할 수 있다. 연구에서는 실시간 계산 자원(Real-Time Computational Resource)에 과도한 부담을 주지 않으면서 관련 불확실성 정보(Relevant Uncertainty Information)를 보존하는 확장 가능한 방법(Scalable Method)을 개발해야 한다.

궁극적으로 신뢰할 수 있는 의사결정(Reliable Decision-Making)을 위해서는 피지컬 인공지능 시스템(Physical AI System)이 자신이 무엇을 알고 있는지, 무엇이 여전히 불확실한지, 행동할 경우 어떤 결과가 발생할 수 있는지 추론해야 한다. 발전은 보정된 불확실성 추정(Calibrated Uncertainty Estimate), 확률적 월드 모델(Probabilistic World Model), 위험 민감형 계획(Risk-Sensitive Planning), 능동적 정보 수집(Active Information Gathering), 신뢰할 수 있는 안전 메커니즘(Dependable Safety Mechanism)에 달려 있다. 이러한 능력은 복잡하고 예측하기 어려운 물리적 환경(Physical Environment)에서 책임감 있게 작동해야 하는 자율 로봇에 필수적이다.

## 07.13. Safe Exploration and Self Improvement

![](images/image13.png){width="7.268055555555556in" height="7.268055555555556in"}

안전한 탐색(Safe Exploration)과 자기 개선(Self-Improvement)은 자율 로봇(Autonomous Robot)이 사람, 장비, 환경을 허용할 수 없는 위험(Unacceptable Risk)에 노출시키지 않으면서 경험으로부터 학습해야 한다는 점에서 피지컬 인공지능(Physical AI)의 핵심 연구 과제이다. 디지털 학습 시스템(Digital Learning System)과 달리 물리적 실험(Physical Experimentation)은 되돌릴 수 없는 손상(Irreversible Damage)을 초래할 수 있다. 따라서 신뢰할 수 있는 로봇(Reliable Robot)은 새로운 행동을 발견하는 이점과 학습 및 배포 전반에서 안전성(Safety)을 유지해야 하는 책임 사이의 균형을 확보해야 한다.

탐색(Exploration)은 로봇이 익숙하지 않은 객체(Unfamiliar Object), 물리적 특성(Physical Property), 환경 구조(Environmental Structure), 행동 전략(Action Strategy)을 발견할 수 있도록 한다. 그러나 가치 있는 정보(Valuable Information)를 제공하는 행동도 충돌(Collision), 불안정성(Instability), 장비 손상(Equipment Damage)을 유발할 수 있다. 안전한 탐색(Safe Exploration)을 위해서는 정보 가치가 높은 실험(Informative Experiment)과 불필요하게 위험한 실험(Unnecessarily Hazardous Experiment)을 구분해야 한다. 목표는 불확실성(Uncertainty)을 완전히 제거하는 것이 아니라 허용 가능한 운영 위험(Operational Risk)을 유지하면서 유용한 지식(Useful Knowledge)을 획득하는 것이다.

탐색-활용 딜레마(Exploration-Exploitation Dilemma)는 학습이 물리적 세계(Physical World)에서 이루어질 때 특히 중요해진다. 활용(Exploitation)은 기존 정책(Established Policy)을 사용하여 알려진 목표(Known Objective)를 달성하는 반면, 탐색(Exploration)은 잠재적으로 더 나은 대안(Alternative)을 조사한다. 지나친 활용은 개선(Improvement)을 제한하고, 통제되지 않은 탐색(Uncontrolled Exploration)은 안전 위험(Safety Hazard)을 발생시킨다. 적응형 전략(Adaptive Strategy)은 예상 학습 이점(Expected Learning Benefit)과 사용 가능한 안전 여유도(Safety Margin)를 기준으로 언제 실험이 정당화되는지 결정해야 한다.

제약 강화학습(Constrained Reinforcement Learning)은 명시적인 안전 요구사항(Safety Requirement)을 준수하면서 행동을 최적화하기 위한 프레임워크(Framework)를 제공한다. 학습 과정(Learning Process)은 작업 보상(Task Reward)만 최대화하는 대신 충돌, 과도한 힘(Excessive Force), 불안정한 움직임(Unstable Motion), 제한 구역 위반(Restricted-Area Violation)에 대한 한계를 포함한다. 이러한 제약(Constraint)은 기대 비용(Expected Cost)이나 위험 척도(Risk Measure)를 통해 표현할 수 있다. 그러나 평균적인 제약을 만족한다고 해서 개별적인 치명적 실패(Catastrophic Failure)까지 반드시 방지되는 것은 아니다.

안전 차폐 장치(Safety Shield)는 탐색 정책(Exploratory Policy)이 사전에 정의된 운영 경계(Operational Boundary)를 위반하는 행동을 실행하지 못하도록 방지할 수 있다. 안전 차폐 장치는 위험한 명령(Unsafe Command)을 거부하거나, 궤적(Trajectory)을 수정하거나, 검증된 대체 제어기(Verified Fallback Controller)를 활성화할 수 있다. 이러한 분리 구조(Separation)는 학습 구성 요소(Learning Component)가 새로운 행동을 제안하는 동안 독립적인 메커니즘(Independent Mechanism)이 핵심 제약(Critical Constraint)을 강제하도록 한다. 그러나 차폐 효과(Shielding Effectiveness)는 정확한 상태 추정(State Estimation)과 충분히 신뢰할 수 있는 안전 모델(Safety Model)에 의존한다.

제어 장벽 함수(Control Barrier Function)와 도달 가능 집합 분석(Reachable-Set Analysis)은 안전한 운영 영역(Safe Operating Region)을 유지하기 위한 수학적 접근법(Mathematical Approach)을 제공한다. 이러한 기법은 후보 제어 행동(Candidate Control Action)이 시간에 따라 지정된 상태 제약(State Constraint)을 유지하는지 평가한다. 이를 통해 충돌 회피(Collision Avoidance), 액추에이터 한계(Actuator Limit), 안정성 보호(Stability Protection)를 지원할 수 있다. 그러나 이러한 기법의 보장(Guarantee)은 모델링 가정(Modeling Assumption), 외란 경계(Disturbance Bound), 계산적으로 처리 가능한 안전 표현(Safety Representation)의 확보 여부에 달려 있다.

시뮬레이션(Simulation)은 실제 배포(Physical Deployment) 이전에 탐색 행동(Exploratory Behavior)을 시험할 수 있는 비교적 위험이 낮은 환경을 제공한다. 로봇은 실제 장비를 반복적으로 위험에 노출시키지 않고도 후보 정책(Candidate Policy)을 평가하고, 합성 실패(Synthetic Failure)를 경험하며, 복구 전략(Recovery Strategy)을 연습할 수 있다. 도메인 무작위화(Domain Randomization)와 디지털 트윈(Digital Twin)은 실험 범위(Experimental Coverage)를 확장할 수 있다. 그러나 시뮬레이션이 모든 물리적 상호작용(Physical Interaction)을 재현할 수는 없으므로 제한 없는 운영(Unrestricted Operation)에 앞서 실제 세계 검증(Real-World Validation)이 필요하다.

시뮬레이션-현실 격차(Simulation-to-Reality Gap, Sim2Real Gap)는 안전한 자기 개선(Safe Self-Improvement)의 주요 장애물이다. 시뮬레이션에서는 신뢰할 수 있어 보이는 정책(Policy)도 모델링되지 않은 마찰(Unmodeled Friction), 센서 성능 저하(Sensor Degradation), 접촉 동역학(Contact Dynamics), 예상하지 못한 인간 행동(Unexpected Human Behavior)에 직면하면 실패할 수 있다. 따라서 안전성 평가(Safety Evaluation)에는 시뮬레이션 충실도(Simulation Fidelity)에 관한 불확실성이 포함되어야 한다. 점진적 배포(Gradual Deployment), 제한된 운영 범위(Restricted Operating Envelope), 통제된 물리적 시험(Controlled Physical Trial)은 적응 과정에서 위험 노출(Risk Exposure)을 줄일 수 있다.

불확실성 인식 탐색(Uncertainty-Aware Exploration)은 예상 정보 이득(Expected Information Gain)과 잠재적 결과(Potential Consequence)를 함께 고려하여 행동의 우선순위를 결정한다. 로봇은 익숙하지 않은 표면(Unfamiliar Surface)을 주행하기 전에 검사하거나, 알려지지 않은 객체(Unknown Object)를 파지하기 전에 낮은 힘의 접촉 시험(Low-Force Contact Test)을 수행할 수 있다. 이러한 실험은 즉시 고위험 행동(High-Risk Action)을 실행하지 않고도 물리적 이해(Physical Understanding)를 향상시킬 수 있다. 신뢰할 수 있는 탐색을 위해서는 추가 정보가 관련된 물리적 비용(Physical Cost)을 정당화하는지 추정해야 한다.

능동 학습(Active Learning)은 개선에 필요한 실제 세계 실험(Real-World Experimentation)의 양을 줄일 수 있다. 로봇은 임의의 경험(Arbitrary Experience)을 수집하는 대신 모델에 특히 유익한 관측(Observation)이나 상호작용(Interaction)을 식별한다. 목표 지향적 데이터 수집(Targeted Data Collection)은 불확실한 객체 특성(Object Property), 드문 실패 조건(Rare Failure Condition), 충분히 이해되지 않은 동역학(Poorly Understood Dynamics)에 집중할 수 있다. 그러나 정보 가치(Information Value)는 안전 제약(Safety Constraint) 및 더 안전한 대안(Safer Alternative)의 가용성과 함께 평가되어야 한다.

자기 개선(Self-Improvement)은 개별 행동(Individual Action)의 학습을 넘어 인식(Perception), 월드 모델(World Model), 계획(Planning), 제어(Control)를 정교화하는 과정으로 확장된다. 운영 경험(Operational Experience)은 체계적인 예측 오류(Systematic Prediction Error), 비효율적인 궤적(Inefficient Trajectory), 반복적인 작업 실패(Recurring Task Failure)를 드러낼 수 있다. 이러한 관측은 모델 업데이트(Model Update)와 정책 개선(Policy Refinement)의 방향을 제시할 수 있다. 핵심 과제는 관측된 개선이 발견 당시의 특정 조건(Specific Condition)을 넘어 일반화(Generalization)되는지 판단하는 것이다.

지속적인 자기 개선(Continual Self-Improvement)은 새로운 학습이 이전에 검증된 능력(Previously Validated Capability)을 저하시킬 위험을 수반한다. 업데이트는 최근 작업(Recent Task)의 성능을 향상시키면서 충돌 회피(Collision Avoidance), 파지 안정성(Grasp Stability), 복구 행동(Recovery Behavior)을 약화시킬 수 있다. 이러한 성능 퇴행(Regression)을 방지하려면 경험 재생(Experience Replay), 보호된 안전 기능(Protected Safety Function), 과거 작업(Historical Task) 전반에 대한 평가가 필요하다. 개선은 고립된 단기 성과(Short-Term Gain)가 아니라 누적된 능력(Accumulated Competence)을 기준으로 측정해야 한다.

오프라인 강화학습(Offline Reinforcement Learning)은 지속적인 물리적 실험 없이 이전에 수집된 경험(Previously Collected Experience)을 사용하여 정책을 개선하는 방법을 제공한다. 과거 궤적(Historical Trajectory)은 성공한 행동과 실패한 행동 모두로부터 학습하는 데 활용될 수 있다. 그러나 정책은 데이터셋(Dataset)에 충분히 표현되지 않은 행동의 가치를 잘못 평가할 수 있다. 따라서 오프라인 개선(Offline Improvement)을 안전하게 배포할 수 있는지 결정할 때 보수적 학습 방법(Conservative Learning Method)과 불확실성 추정(Uncertainty Estimation)이 중요하다.

인간 시연(Human Demonstration)과 교정 피드백(Corrective Feedback)은 탐색을 유용하고 허용 가능한 행동으로 유도할 수 있다. 운영자(Operator)는 안전한 조작(Safe Manipulation)을 시연하거나, 위험한 조건(Hazardous Condition)을 식별하거나, 자율 행동(Autonomous Behavior)이 불확실해질 때 개입할 수 있다. 이러한 지침(Guidance)은 탐색 비용(Exploration Cost)을 줄이고 작업 관련성(Task Relevance)을 높일 수 있다. 그러나 인간 피드백(Human Feedback)은 일관되지 않을 수 있으며, 시연이 배포 중 발생하는 모든 실패 조건(Failure Condition)을 포괄하지 못할 수도 있다.

단계적 검증 프로세스(Staged Validation Process)는 실험적 학습(Experimental Learning)과 운영 배포(Operational Deployment)를 연결할 수 있다. 후보 모델(Candidate Model)은 먼저 오프라인 평가(Offline Evaluation), 시뮬레이션 시험(Simulation Testing), 통제된 물리적 시험(Controlled Physical Trial), 점진적으로 확대되는 현장 시험(Field Testing)을 거칠 수 있다. 각 단계에서는 작업 성능(Task Performance)과 안전성에 대한 측정 가능한 수용 기준(Acceptance Criteria)을 설정해야 한다. 배포는 의도된 운영 조건(Intended Operating Condition)을 뒷받침하는 증거가 확보된 경우에만 진행해야 하며, 성능 퇴행이 발생하면 롤백 메커니즘(Rollback Mechanism)을 사용할 수 있어야 한다.

런타임 모니터링(Runtime Monitoring)은 충분히 검증된 정책이라도 익숙하지 않은 조건(Unfamiliar Condition)에 직면할 수 있으므로 필요하다. 모니터링 시스템(Monitoring System)은 비정상적인 관측(Unusual Observation), 예측 실패(Prediction Failure), 과도한 힘(Excessive Force), 예상 궤적(Expected Trajectory)으로부터의 이탈을 탐지할 수 있다. 안전 여유도(Safety Margin)가 감소하면 로봇은 속도를 줄이거나, 지원을 요청하거나, 보호된 제어기(Protected Controller)로 전환할 수 있다. 이러한 메커니즘은 예상하지 못한 행동의 결과를 제한하면서 적응(Adaptation)을 가능하게 한다.

복구 능력(Recovery Competence)은 안전한 탐색(Safe Exploration)의 중요한 구성 요소이다. 로봇은 실패한 행동(Failed Action)을 인식하고, 물리적 상태(Physical State)를 안정화하며, 알려진 안전 구성(Known Safe Configuration)으로 복귀하는 방법을 학습해야 한다. 복구에는 객체를 놓거나, 장애물(Obstacle)로부터 후퇴하거나, 실행 불가능한 작업(Infeasible Task)을 포기하는 행동이 포함될 수 있다. 그러나 부적절한 교정 행동(Corrective Action)은 기존 실패의 심각도(Failure Severity)를 높일 수 있으므로 복구 전략(Recovery Strategy) 자체도 검증되어야 한다.

플릿 규모 자기 개선(Fleet-Scale Self-Improvement)은 여러 로봇의 경험을 통합하여 학습을 가속할 수 있다. 드문 실패(Rare Failure), 성공적인 적응(Successful Adaptation), 익숙하지 않은 환경 조건(Environmental Condition)은 공유 훈련 데이터셋(Shared Training Dataset)에 기여할 수 있다. 중앙집중식 학습(Centralized Learning)이나 연합학습(Federated Learning)은 개선된 모델(Improved Model)을 플릿(Fleet) 전체에 배포할 수 있다. 그러나 광범위한 배포 이전에 하드웨어(Hardware), 보정(Calibration), 운영 환경(Operating Environment), 안전 요구사항(Safety Requirement)의 차이를 고려하여 업데이트를 평가해야 한다.

자기 개선 로봇(Self-Improving Robot)은 언제 학습을 중단해야 하는지 결정하는 메커니즘도 필요하다. 지속적인 적응(Continual Adaptation)이 항상 유익한 것은 아니며, 특히 데이터 품질(Data Quality)이 저하되거나 운영 조건이 위험해지는 경우에는 더욱 그렇다. 학습률 제한(Learning-Rate Limit), 불확실성 임계값(Uncertainty Threshold), 성능 모니터링(Performance Monitoring)은 불안정한 업데이트(Unstable Update)를 방지하는 데 도움이 될 수 있다. 신뢰할 수 있는 운영(Reliable Operation)을 유지하면서 학습을 일시 중단하는 능력 자체가 자율 지능(Autonomous Intelligence)의 중요한 측면이다.

안전한 탐색(Safe Exploration)의 평가는 학습 효율성(Learning Efficiency), 안전 위반(Safety Violation), 복구 성공률(Recovery Success), 성능 유지(Performance Retention)를 고려해야 한다. 빠르게 학습하더라도 위험한 사건(Hazardous Event)을 빈번하게 발생시키는 시스템은 성공적이라고 평가할 수 없다. 벤치마크(Benchmark)에는 드문 외란(Rare Disturbance), 익숙하지 않은 객체(Unfamiliar Object), 센서 고장(Sensor Failure), 변화하는 운영 제약(Operational Constraint)이 포함되어야 한다. 반복적인 업데이트 이후에도 개선 효과가 신뢰성 있게 유지되는지 판단하려면 장기간 시험(Long-Duration Testing)이 필요하다.

아직 해결되지 않은 연구 과제(Unresolved Research Challenge)는 자율적 개선(Autonomous Improvement)이 안전성을 훼손하지 않는다는 신뢰할 수 있는 증거(Trustworthy Evidence)를 확립하는 것이다. 통계적 시험(Statistical Testing)만으로는 극히 드문 실패(Extremely Rare Failure)에 대해 충분한 보증(Assurance)을 제공하기 어려울 수 있다. 형식 검증(Formal Verification), 런타임 보증(Runtime Assurance), 경험적 평가(Empirical Evaluation), 보수적 배포(Conservative Deployment)를 결합하면 신뢰도를 강화할 수 있다. 그러나 학습된 모델(Learned Model)이 복잡하고 부분적으로만 관측 가능한 물리적 환경(Partially Observable Physical Environment)과 상호작용하는 경우 안전 보장(Safety Guarantee)을 확보하기는 여전히 어렵다.

또 다른 과제는 학습 과정(Learning Process) 자체를 자율적으로 수정하는 문제이다. 발전된 로봇(Advanced Robot)은 축적된 경험(Accumulated Experience)을 기반으로 탐색 전략(Exploration Strategy), 기억 구조(Memory Structure), 계획 아키텍처(Planning Architecture)를 조정할 수 있을 것이다. 이러한 변화는 적응성(Adaptability)을 향상시킬 수 있지만, 이전 안전성 평가(Previous Safety Assessment)의 기반이 된 가정도 변경할 수 있다. 따라서 신뢰할 수 있는 자기 수정(Reliable Self-Modification)을 위해서는 명시적인 경계(Explicit Boundary), 추적 가능한 업데이트(Traceable Update), 독립적인 검증 메커니즘(Independent Validation Mechanism)이 필요하다.

궁극적으로 안전한 탐색(Safe Exploration)과 자기 개선(Self-Improvement)은 운영 신뢰성(Operational Reliability)을 희생하지 않으면서 경험을 통해 더욱 높은 능력을 갖추는 피지컬 인공지능 시스템(Physical AI System)을 구현하는 것을 목표로 한다. 이를 위해서는 불확실성 추정(Uncertainty Estimation), 제약 학습(Constrained Learning), 예측 월드 모델(Predictive World Model), 안전 감독(Safety Supervision), 지속적 검증(Continuous Validation)의 통합이 필요하다. 장기적인 목표는 제한 없는 자율 실험(Unrestricted Autonomous Experimentation)이 아니라 입증 가능한 안전 경계(Demonstrable Safety Boundary) 내에서 누적적 개선(Cumulative Improvement)을 만들어내는 체계적인 학습(Disciplined Learning)이다.

## 07.14. Morphology Intelligence Co Design

![](images/image14.png){width="7.268055555555556in" height="7.268055555555556in"}

형태-지능 공동 설계(Morphology-Intelligence Co-Design)는 로봇의 신체 구현(Embodiment)과 계산 지능(Computational Intelligence)을 하나의 시스템을 구성하는 상호 연결된 요소로 다루는 피지컬 인공지능(Physical AI)의 새로운 연구 방향이다. 전통적인 로보틱스(Traditional Robotics)는 일반적으로 기계 구조(Mechanical Structure)를 먼저 설계한 다음 인식(Perception), 계획(Planning), 제어 알고리즘(Control Algorithm)을 개발한다. 반면 공동 설계(Co-Design)는 신체 기하학(Body Geometry), 액추에이터(Actuator), 센서(Sensor), 재료(Material), 학습 아키텍처(Learning Architecture)가 달성 가능한 행동(Achievable Behavior)을 공동으로 결정하는 방식을 고려한다.

로봇 형태(Robot Morphology)는 자율 시스템(Autonomous System)이 수행할 수 있는 물리적 상호작용(Physical Interaction)의 범위를 결정함으로써 지능(Intelligence)에 영향을 미친다. 사지 길이(Limb Length), 관절 배치(Joint Placement), 질량 분포(Mass Distribution), 순응성(Compliance), 접촉 표면(Contact Surface)은 로봇이 이동하고 객체를 조작하는 방식을 결정한다. 이러한 특성은 가능한 행동(Possible Action)을 제한하는 동시에 효율적인 행동(Efficient Behavior)을 구현할 기회를 제공한다. 따라서 지능은 행동을 실행하는 신체(Body)와 독립적으로 평가할 수 없다.

형태적 연산(Morphological Computation)은 물리적 구조(Physical Structure)가 명시적인 계산 제어(Explicit Computational Control)를 필요로 하는 기능을 대신 수행하는 방식을 설명한다. 수동적 순응성(Passive Compliance)은 충격을 흡수하고, 탄성 구성 요소(Elastic Component)는 에너지를 저장하며, 기계적 링크 구조(Mechanical Linkage)는 움직임을 조정할 수 있다. 이러한 특성은 제어 알고리즘(Control Algorithm)의 부담을 줄인다. 그러나 수동적 메커니즘(Passive Mechanism)은 운영 조건(Operating Condition)이 설계 당시 예상한 조건과 크게 달라지면 오히려 단점이 될 수 있다.

공동 설계(Co-Design)는 기계적 성능(Mechanical Performance), 센싱 능력(Sensing Capability), 제어 복잡성(Control Complexity), 계산 비용(Computational Cost)을 함께 고려하는 최적화(Optimization)를 요구한다. 관절(Joint)이 추가된 로봇은 조작 민첩성(Dexterity)을 확보할 수 있지만, 더욱 정교한 협조 제어(Coordination)와 높은 에너지 소비(Energy Consumption)가 필요할 수 있다. 단순한 메커니즘(Simpler Mechanism)은 신뢰성(Reliability)을 향상시키는 대신 작업 범용성(Task Versatility)을 제한할 수 있다. 핵심 과제는 불필요한 기계적 복잡성(Mechanical Complexity)을 도입하지 않으면서 폭넓은 능력을 지원하는 신체 구조(Embodiment)를 식별하는 것이다.

형태(Morphology)와 학습 효율성(Learning Efficiency)의 관계는 범용 로봇(General-Purpose Robot)에서 특히 중요하다. 일부 신체 구성(Body Configuration)은 강화학습(Reinforcement Learning)이나 모방학습(Imitation Learning)을 통해 유용한 행동을 더 쉽게 발견하도록 한다. 반면 다른 구성은 효과적인 행동을 위해 정밀한 협조 제어(Precise Coordination)가 필요하므로 탐색 과정(Exploration Landscape)을 어렵게 만든다. 학습을 단순화하도록 형태를 설계하면 훈련 데이터 요구량(Training Data Requirement)을 줄이고 학습된 정책(Learned Policy)의 전이(Transfer)를 개선할 수 있다.

액추에이터 선택(Actuator Selection)은 물리적 설계(Physical Design)와 지능형 제어(Intelligent Control) 사이의 상호작용에 큰 영향을 미친다. 고토크 액추에이터(High-Torque Actuator)는 큰 힘을 제공하지만 질량(Mass), 발열(Heat Generation), 전력 소비(Power Consumption)를 증가시킬 수 있다. 순응형 액추에이터(Compliant Actuator)는 상호작용 안전성(Interaction Safety)과 충격 허용 능력(Impact Tolerance)을 향상시키지만 추가적인 동역학적 복잡성(Dynamic Complexity)을 발생시킨다. 공동 설계는 의도된 작업(Intended Task)과 함께 액추에이터 대역폭(Actuator Bandwidth), 토크 밀도(Torque Density), 효율(Efficiency), 제어 가능성(Controllability)을 고려해야 한다.

센서 배치(Sensor Placement)는 형태-지능 통합(Morphology-Intelligence Integration)의 또 다른 핵심 요소이다. 카메라(Camera), 촉각 센서(Tactile Sensor), 힘 센서(Force Sensor), 관성 측정 장치(Inertial Measurement Unit, IMU)가 제공하는 정보의 유용성은 물리적 설치 위치(Physical Location)에 따라 달라진다. 부적절한 센서 기하학(Sensor Geometry)은 지속적인 사각지대(Blind Spot)나 모호한 관측(Ambiguous Observation)을 발생시킬 수 있다. 센싱(Sensing)과 신체 구현(Embodiment)을 공동으로 최적화하면 불필요한 센서 중복(Sensor Redundancy)을 줄이면서 관측 가능성(Observability)을 향상시킬 수 있다.

소프트 로보틱스(Soft Robotics)는 형태(Morphology)가 적응형 물리적 행동(Adaptive Physical Behavior)에 직접 기여하는 방식을 보여준다. 유연한 구조(Flexible Structure)는 객체 주변으로 변형되고, 접촉력(Contact Force)을 분산하며, 불확실한 기하학(Uncertain Geometry)에 적응한다. 이러한 특성은 파지(Grasping)와 섬세한 재료(Delicate Material)의 조작을 단순화할 수 있다. 그러나 변형 가능한 신체(Deformable Body)의 동역학은 비선형적(Nonlinear)이고 분산적(Distributed)이며 완전한 관측이 어렵기 때문에 모델링(Modeling)과 제어(Control)는 여전히 어려운 과제이다.

다족 보행(Legged Locomotion)은 형태와 제어의 상호의존성(Morphology-Control Interdependence)을 보여주는 대표적인 사례이다. 다리 비율(Leg Proportion), 관절 구성(Joint Configuration), 발의 기하학(Foot Geometry), 신체 질량 분포(Body Mass Distribution)는 안정성(Stability), 속도(Speed), 지형 적응성(Terrain Adaptability)에 영향을 미친다. 특정 형태에 최적화된 제어기(Controller)는 다른 형태에서 성능이 저하될 수 있다. 다리 설계(Leg Design)와 보행 정책(Locomotion Policy)을 공동으로 최적화하면 어려운 환경을 더욱 효율적이고 강건하게 이동하는 로봇을 개발할 수 있다.

이동 조작(Mobile Manipulation)은 이동 능력(Locomotion Capability)과 조작 능력(Manipulation Capability) 사이의 추가적인 절충 관계(Tradeoff)를 발생시킨다. 대형 매니퓰레이터(Large Manipulator)는 작업 공간 도달 범위(Workspace Reach)를 확장하지만 플랫폼 불안정성(Platform Instability)과 에너지 요구량(Energy Demand)을 증가시킬 수 있다. 소형 이동 플랫폼(Compact Mobile Base)은 기동성(Maneuverability)을 향상시키지만 적재 능력(Payload)과 운영 범위(Operational Range)를 제한할 수 있다. 공동 설계는 개별 하위 시스템(Subsystem)을 독립적으로 최적화하기보다 도달 가능성(Reachability), 안정성(Stability), 이동성(Mobility), 작업 요구사항(Task Requirement)의 균형을 고려해야 한다.

미분 가능 시뮬레이션(Differentiable Simulation)은 물리적 매개변수(Physical Parameter)와 제어 정책(Control Policy)을 공동으로 최적화하기 위한 잠재적인 방법을 제공한다. 시뮬레이션 동역학(Simulated Dynamics)을 통해 기울기(Gradient)를 전파하여 신체 치수(Body Dimension), 재료 특성(Material Property), 제어기 매개변수(Controller Parameter)를 조정할 수 있는 경우가 있다. 이러한 접근법은 광범위한 물리적 시제품 제작(Physical Prototyping)에 비해 설계 탐색(Design Exploration)을 가속할 수 있다. 그러나 접촉 불연속성(Contact Discontinuity), 모델링 오류(Modeling Error), 제조 제약(Manufacturing Constraint)은 실제 적용 가능성을 제한한다.

진화적 최적화(Evolutionary Optimization)는 형태(Morphology)와 지능(Intelligence)의 효과적인 조합을 발견하기 위한 또 다른 프레임워크(Framework)를 제공한다. 후보 로봇 설계(Candidate Robot Design)는 시뮬레이션을 통해 평가되며, 성공적인 구조(Structure)와 제어기(Controller)는 후속 세대(Subsequent Generation)의 설계를 유도한다. 이러한 방법은 인간 설계자(Human Designer)가 간과할 수 있는 비전통적인 구성(Unconventional Configuration)을 탐색할 수 있다. 주요 한계에는 계산 비용(Computational Expense), 시뮬레이션 편향(Simulation Bias), 진화적으로 생성된 설계(Evolved Design)를 실제 제조 가능한 하드웨어(Manufacturable Hardware)로 전환하기 어려운 문제가 포함된다.

작업 다양성(Task Diversity)은 하나의 활동에 최적화된 신체가 다른 활동에서는 성능이 저하될 수 있기 때문에 형태 최적화(Morphology Optimization)를 복잡하게 만든다. 빠른 이동(Rapid Locomotion)을 위해 설계된 경량 로봇(Lightweight Robot)은 산업용 조작(Industrial Manipulation)에 필요한 힘을 갖추지 못할 수 있다. 따라서 범용 신체 구현(General-Purpose Embodiment)은 전문화(Specialization)와 적응성(Adaptability)의 균형을 요구한다. 모듈형 하드웨어(Modular Hardware), 교체 가능한 엔드 이펙터(Interchangeable End Effector), 재구성 가능한 구조(Reconfigurable Structure)는 실용적인 절충안을 제공할 수 있다.

형태적 적응(Morphological Adaptation)은 공동 설계를 고정된 기계 구조(Fixed Mechanical Structure) 이상으로 확장한다. 강성 조절(Adjustable Stiffness), 가변 기하학(Variable Geometry), 재구성 가능한 사지(Reconfigurable Limb)를 갖춘 로봇은 변화하는 작업에 맞춰 물리적 특성(Physical Property)을 수정할 수 있다. 이러한 능력은 행동 공간(Action Space)을 확장하지만 계획 및 제어 복잡성(Planning and Control Complexity)도 증가시킨다. 지능형 시스템(Intelligent System)은 물리적 재구성(Physical Reconfiguration)이 시간과 에너지 비용(Time and Energy Cost)을 정당화할 만큼 충분한 이점을 제공하는지 판단해야 한다.

에너지 효율성(Energy Efficiency)은 형태-지능 공동 설계(Morphology-Intelligence Co-Design)의 근본적인 목표이다. 기계 구조(Mechanical Structure)는 에너지 손실(Energy Loss), 액추에이터 부하(Actuator Loading), 균형(Balance), 지속적인 보정 제어(Continuous Corrective Control)의 필요성에 영향을 미친다. 수동 동역학(Passive Dynamics)과 적절한 질량 분포(Mass Distribution)는 계산 및 기계적 노력(Computational and Mechanical Effort)을 줄일 수 있다. 그러나 에너지 소비(Energy Consumption)의 최적화가 안전성(Safety), 강건성(Robustness), 익숙하지 않은 운영 조건(Unfamiliar Operating Condition)에 대응하는 능력을 훼손해서는 안 된다.

하드웨어 인식 학습(Hardware-Aware Learning)은 훈련 이후 실행 불가능한 행동(Infeasible Behavior)을 발견하는 대신 훈련 과정에서 물리적 한계(Physical Limitation)를 준수하는 정책을 학습하도록 한다. 토크 제한(Torque Limit), 관절 가동 범위(Joint Range), 열적 제약(Thermal Constraint), 액추에이터 지연(Actuator Delay), 센서 특성(Sensor Characteristic)은 학습 과정(Learning Process)에 영향을 미쳐야 한다. 이러한 요소를 반영하면 실제 세계 배포 신뢰성(Real-World Deployment Reliability)을 향상시킬 수 있다. 핵심 과제는 복잡한 하드웨어 제약(Hardware Restriction)을 정확하게 표현하면서 학습 유연성(Learning Flexibility)을 유지하는 것이다.

신체 간 전이(Cross-Embodiment Transfer)는 지능의 어떤 측면이 형태(Morphology)와 독립적으로 유지될 수 있는지에 관한 질문을 제기한다. 상위 수준의 작업 개념(High-Level Task Concept)은 바퀴형 로봇(Wheeled Robot), 사족 보행 로봇(Quadruped Robot), 휴머노이드(Humanoid) 사이에서 전이될 수 있지만, 하위 수준의 운동 정책(Low-Level Motor Policy)은 상당한 적응(Adaptation)을 요구하는 경우가 많다. 목표(Goal), 객체(Object), 물리적 행동 가능성(Physical Affordance)에 대한 공유 표현(Shared Representation)은 이러한 전이를 지원할 수 있다. 효과적인 공동 설계는 재사용 가능한 지능(Reusable Intelligence)과 신체 특화 제어(Embodiment-Specific Control)를 구분해야 한다.

제조 실현 가능성(Manufacturing Feasibility)은 순수한 계산적 최적화(Computational Optimization)가 간과할 수 있는 현실적인 제약을 도입한다. 복잡한 구조(Complex Structure)는 시뮬레이션에서 우수한 성능을 달성하더라도 비용이 높고, 취약하며, 유지보수가 어려울 수 있다. 재료 가용성(Material Availability), 조립 공차(Assembly Tolerance), 수리 용이성(Repairability), 구성 요소 표준화(Component Standardization)는 실제 배포(Real Deployment)에 영향을 미친다. 성공적인 공동 설계는 엔지니어링 경제성(Engineering Economics)과 수명주기 고려사항(Lifecycle Consideration)을 최적화 목표(Optimization Objective)에 통합해야 한다.

안전 요구사항(Safety Requirement) 역시 형태(Morphology)와 지능(Intelligence)의 관계를 결정한다. 둥근 표면(Rounded Surface), 순응형 관절(Compliant Joint), 안정적인 지지 기하학(Stable Support Geometry), 기계적으로 제한된 힘(Mechanically Limited Force)은 소프트웨어 개입(Software Intervention)이 필요해지기 전에 위험을 줄일 수 있다. 이러한 본질적 안전 기능(Inherent Safety Feature)은 학습된 정책(Learned Policy)과 런타임 모니터링(Runtime Monitoring)을 보완한다. 신체 자체에 안전성을 내재화하면 순수한 알고리즘적 방법(Algorithmic Method)만으로는 보장하기 어려운 제어 실패(Control Failure)에 대한 보호 기능을 제공할 수 있다.

형태-지능 공동 설계(Morphology-Intelligence Co-Design)의 평가는 개별적인 기계 구성 요소(Mechanical Component)나 알고리즘 구성 요소(Algorithmic Component)가 아니라 완전한 시스템(Complete System)을 비교해야 한다. 관련 평가 지표(Evaluation Metric)에는 작업 성공률(Task Success), 에너지 효율성(Energy Efficiency), 강건성(Robustness), 학습 속도(Learning Speed), 적응성(Adaptability), 유지보수 비용(Maintenance Cost), 안전성(Safety)이 포함된다. 실험에서는 형태에 따른 개선과 더 큰 모델(Larger Model) 또는 추가 훈련(Additional Training)에 따른 개선을 구분해야 한다. 신체 구현(Embodiment)마다 능력과 제약이 다르므로 표준화된 평가(Standardized Evaluation)는 여전히 어렵다.

주요 미해결 연구 질문(Open Research Question) 중 하나는 가능한 로봇 신체(Robot Body)의 탐색 공간(Search Space)에 관한 것이다. 연속적인 치수(Continuous Dimension), 이산적인 메커니즘(Discrete Mechanism), 재료 선택(Material Choice), 센서 구성(Sensor Configuration), 제어 아키텍처(Control Architecture)는 방대한 최적화 문제(Optimization Problem)를 형성한다. 효율적인 탐색(Efficient Search)을 위해서는 유용한 설계 사전 지식(Design Prior), 계층적 표현(Hierarchical Representation), 신뢰할 수 있는 시뮬레이션(Reliable Simulation)이 필요하다. 과도한 계산이나 물리적 시제품 제작 없이 이러한 공간을 탐색하는 방법의 개발은 여전히 중요한 과제이다.

또 다른 미해결 문제(Unresolved Issue)는 로봇의 운영 수명(Operational Lifetime) 전반에서 형태(Morphology)와 지능(Intelligence)이 함께 개선될 수 있는지에 관한 것이다. 소프트웨어(Software)는 빠르게 적응할 수 있지만 기계적 변경(Mechanical Change)은 일반적으로 물리적 교체(Physical Replacement)나 재구성(Reconfiguration)을 요구한다. 미래 시스템(Future System)은 모듈형 하드웨어 진화(Modular Hardware Evolution)와 지속 학습(Continual Learning)을 결합하여 점진적인 능력 개발(Progressive Capability Development)을 지원할 수 있다. 이러한 접근법은 호환성(Compatibility), 검증(Validation), 기존에 획득한 기술(Previously Acquired Skill)의 보존을 관리해야 한다.

궁극적으로 형태-지능 공동 설계(Morphology-Intelligence Co-Design)는 고도화된 피지컬 인공지능(Advanced Physical AI)이 신체(Body), 센서(Sensor), 액추에이터(Actuator), 학습 시스템(Learning System), 제어 아키텍처(Control Architecture)의 조화로운 개발을 통해 등장할 것임을 시사한다. 지능은 단순히 기계적 한계(Mechanical Limitation)를 보완하는 역할에 머물러서는 안 되며, 하드웨어 설계(Hardware Design) 역시 고정된 계산 능력(Computational Capability)을 전제로 해서는 안 된다. 범용 물리 지능(General Physical Intelligence)을 향한 발전은 복잡한 행동을 더 쉽게 학습하고, 더 안전하게 실행하며, 더 효율적으로 지속할 수 있도록 하는 신체 구현(Embodiment)을 발견하는 데 달려 있을 수 있다.

## 07.15. Energy Efficient Physical Intelligence

![](images/image15.png){width="7.268055555555556in" height="7.268055555555556in"}

에너지 효율적인 물리 지능(Energy-Efficient Physical Intelligence)은 자율 로봇(Autonomous Robot)이 제한된 에너지 자원(Energy Resource)을 유용한 인식(Perception), 추론(Reasoning), 물리적 행동(Physical Action)으로 전환해야 한다는 점에서 피지컬 인공지능(Physical AI)의 근본적인 과제이다. 순수한 디지털 시스템(Digital System)과 달리 로봇은 연산(Computation), 센싱(Sensing), 구동(Actuation), 통신(Communication), 환경과의 상호작용(Environmental Interaction)을 통해 에너지를 소비한다. 지속 가능한 자율성(Sustained Autonomy)을 달성하려면 계산 효율성(Computational Efficiency)과 기계적 효율성(Mechanical Efficiency)을 별개의 목표로 다루는 대신 이러한 과정을 통합적으로 최적화해야 한다.

에너지 소비(Energy Consumption)는 운영 지속시간(Operational Endurance), 이동성(Mobility), 적재 능력(Payload Capacity), 시스템 신뢰성(System Reliability)에 직접적인 영향을 미친다. 로봇이 고도화된 인식 및 계획 능력(Perception and Planning Capability)을 갖추더라도 에너지 요구량(Energy Requirement)이 사용 가능한 배터리 용량(Battery Capacity)을 초과하면 실용성이 떨어진다. 배터리 크기(Battery Size)를 늘리면 추가적인 질량(Mass)이 발생하여 이동 에너지 비용(Locomotion Cost)이 증가하고 기동성(Maneuverability)이 감소할 수 있다. 따라서 에너지 효율적인 지능(Energy-Efficient Intelligence)은 전력 가용성(Power Availability), 물리적 설계(Physical Design), 작업 성능(Task Performance) 사이의 상호작용을 고려해야 한다.

피지컬 인공지능의 에너지 효율성(Energy Efficiency)은 초당 계산 연산량(Computational Operations per Second)이나 신경망 추론 지연시간(Neural Network Inference Latency)만으로 측정할 수 없다. 의미 있는 평가(Meaningful Evaluation)를 위해서는 성공적으로 완료한 작업(Successful Task), 이동 거리(Distance Traveled), 조작한 객체(Object Manipulated), 완료한 임무(Mission Completed)당 소비 에너지(Energy Consumed)를 고려해야 한다. 계산 비용이 높은 계획 알고리즘(Planning Algorithm)도 비효율적인 움직임을 방지하여 전체 에너지 소비를 줄일 수 있다. 반대로 경량 모델(Lightweight Model)은 반복적으로 잘못된 물리적 의사결정(Physical Decision)을 생성하면 에너지를 낭비할 수 있다.

구동(Actuation)은 이동 로봇(Mobile Robot)과 조작 로봇(Manipulation Robot)에서 주요 에너지 수요(Energy Demand)를 차지하는 경우가 많다. 모터(Motor)는 안정성(Stability)과 정밀도(Precision)를 유지하면서 관성(Inertia), 마찰(Friction), 중력(Gravity), 외부 하중(External Load)을 극복해야 한다. 비효율적인 운동 궤적(Motion Trajectory)은 계산 작업량(Computational Workload)이 작더라도 상당한 에너지를 소비할 수 있다. 기계 설계(Mechanical Design), 궤적 생성(Trajectory Generation), 피드백 제어(Feedback Control)를 공동으로 최적화하면 불필요한 가속(Acceleration), 제동(Braking), 보정 움직임(Corrective Movement)을 줄일 수 있다.

형태(Morphology)는 물리적 작업(Physical Task)을 수행하는 데 필요한 에너지에 큰 영향을 미친다. 신체 질량 분포(Body Mass Distribution), 관절 구성(Joint Configuration), 동력 전달 효율(Transmission Efficiency), 바퀴 기하학(Wheel Geometry), 순응형 구조(Compliant Structure)는 이동 및 조작 비용(Locomotion and Manipulation Cost)에 영향을 준다. 수동적 기계 동역학(Passive Mechanical Dynamics)은 경우에 따라 지속적인 능동 제어(Active Control)를 대체할 수 있다. 그러나 이상적인 조건(Ideal Condition)에서 에너지 효율에 최적화된 설계는 지형(Terrain), 적재 하중(Payload), 환경 외란(Environmental Disturbance)이 변화하면 비효율적이거나 불안정해질 수 있다.

에너지 인식 계획(Energy-Aware Planning)은 대안 행동(Alternative Action)의 전력 소비 결과(Power Consequence)를 고려함으로써 기존의 작업 최적화(Task Optimization)를 확장한다. 이동 로봇은 급경사(Steep Gradient)나 반복적인 가속을 피하기 위해 더 길지만 평탄한 경로(Smoother Route)를 선택할 수 있다. 매니퓰레이터(Manipulator)는 지속적인 유지 토크(Holding Torque)를 줄이는 파지 방식(Grasp)을 선택할 수 있다. 이러한 의사결정에는 행동(Action), 물리적 조건(Physical Condition), 실행 시간(Execution Time), 에너지 소비(Energy Consumption)를 연결하는 예측 모델(Predictive Model)이 필요하다.

배터리 상태 추정(Battery State Estimation)은 신뢰할 수 있는 에너지 인식 자율성(Energy-Aware Autonomy)을 위해 필수적이다. 잔여 용량(Remaining Capacity)만으로는 사용 가능한 에너지(Usable Energy)를 완전히 설명할 수 없는데, 온도(Temperature), 노화(Aging), 방전율(Discharge Rate), 부하 변동(Load Variation)이 배터리 성능(Battery Performance)에 영향을 미치기 때문이다. 충전 상태(State of Charge, SoC)와 건강 상태(State of Health, SoH)의 추정은 운영 계획(Operational Planning)을 지원할 수 있다. 그러나 부정확한 배터리 모델(Battery Model)은 로봇이 운영 지속시간(Endurance)을 과대평가하게 만들어 임무 실패(Mission Failure)나 안전하지 않은 시스템 종료(Unsafe Shutdown)를 초래할 수 있다.

에너지 효율적인 인식(Energy-Efficient Perception)을 위해서는 운영 요구사항(Operational Need)에 따라 센싱 노력(Sensing Effort)을 조절해야 한다. 고해상도 카메라(High-Resolution Camera), 고밀도 라이다 측정(Dense LiDAR Measurement), 지속적인 다중 모달 처리(Continuous Multimodal Processing)는 상세한 환경 정보(Environmental Information)를 제공하지만 상당한 전력을 소비한다. 적응형 센싱(Adaptive Sensing)은 예측 가능한 조건에서 샘플링 속도(Sampling Rate)를 낮추거나 불필요한 센서를 비활성화할 수 있다. 그러나 에너지 절약 정책(Energy-Saving Policy)이 일반적인 인식 작업량(Perception Workload)을 제한하더라도 핵심 안전 관측(Critical Safety Observation)은 계속 이용할 수 있어야 한다.

신경망 아키텍처(Neural Network Architecture) 역시 물리 지능(Physical Intelligence)의 에너지 요구량에 영향을 미친다. 대규모 시각-언어-행동 모델(Vision-Language-Action Model, VLA)은 유연한 추론(Flexible Reasoning)을 제공할 수 있지만 상당한 메모리 대역폭(Memory Bandwidth)과 가속기 전력(Accelerator Power)을 요구한다. 양자화(Quantization), 가지치기(Pruning), 지식 증류(Knowledge Distillation), 효율적인 어텐션 메커니즘(Efficient Attention Mechanism)은 추론 비용(Inference Cost)을 줄일 수 있다. 이러한 기법의 실제 가치는 정확도 저하(Accuracy Degradation), 응답 지연(Response Latency), 잘못된 물리적 행동(Incorrect Physical Action)의 결과를 함께 고려하여 평가해야 한다.

적응형 연산(Adaptive Computation)은 로봇이 작업 난이도(Task Difficulty)와 불확실성(Uncertainty)에 따라 처리 자원(Processing Resource)을 할당하도록 한다. 일상적인 내비게이션(Routine Navigation)에는 경량 추론(Lightweight Inference)만 필요할 수 있지만, 익숙하지 않은 조작(Unfamiliar Manipulation)에는 더욱 집중적인 추론(Intensive Reasoning)이 정당화될 수 있다. 조기 종료 신경망(Early-Exit Network), 계층적 제어기(Hierarchical Controller), 선택적 모델 활성화(Selective Model Activation)는 가능한 접근법이다. 아직 해결되지 않은 과제는 추가 연산(Additional Computation)이 에너지 소비를 정당화할 만큼 의사결정을 개선하는 시점을 예측하는 것이다.

엣지 컴퓨팅(Edge Computing)은 로컬 처리(Local Processing)와 원격 지능 서비스(Remote Intelligence Service) 사이의 절충 관계(Tradeoff)를 발생시킨다. 온보드 연산(Onboard Computation)은 통신 의존성(Communication Dependence)을 줄이고 저지연 제어(Low-Latency Control)를 지원할 수 있지만, 고성능 가속기(Powerful Accelerator)는 전력 및 열적 요구량(Electrical and Thermal Demand)을 증가시킨다. 일부 작업을 외부로 오프로딩(Offloading)하면 로컬 연산 비용을 절약할 수 있지만 통신 에너지(Communication Energy)를 소비하고 네트워크 지연(Network Delay)을 발생시킨다. 최적의 작업 배분(Optimal Allocation)은 작업 긴급성(Task Urgency), 연결성(Connectivity), 개인정보 보호 요구사항(Privacy Requirement), 사용 가능한 전력(Available Power)에 따라 달라진다.

열 관리(Thermal Management)는 에너지 효율성(Energy Efficiency)과 계산 신뢰성(Computational Reliability)을 연결하는 또 다른 요소이다. 고전력 프로세서(High-Power Processor)와 액추에이터(Actuator)는 열을 발생시키며, 능동 냉각(Active Cooling)이나 작동 주파수 감소(Reduced Operating Frequency)가 필요할 수 있다. 열 스로틀링(Thermal Throttling)은 추론 지연시간(Inference Latency)과 제어 응답성(Control Responsiveness)을 변화시킬 수 있다. 따라서 지능형 작업 부하 스케줄링(Intelligent Workload Scheduling)은 순간적인 계산 처리량(Instantaneous Computational Throughput)만 최적화하기보다 온도(Temperature), 냉각 능력(Cooling Capacity), 지속 성능(Sustained Performance)을 고려해야 한다.

에너지 효율적인 행동(Energy-Efficient Behavior)을 학습하려면 물리적 비용(Physical Cost)을 정확하게 표현하는 보상 함수(Reward Function)가 필요하다. 강화학습(Reinforcement Learning)은 과도한 토크(Excessive Torque), 불필요한 움직임(Unnecessary Movement), 장시간 작업 실행(Prolonged Task Execution)에 페널티(Penalty)를 부여할 수 있다. 그러나 잘못 설계된 에너지 페널티(Energy Penalty)는 느리거나 불안정하거나 완료되지 않은 행동을 유도할 수 있다. 다목적 최적화(Multi-Objective Optimization)는 에너지 소비(Energy Consumption)와 작업 성공(Task Success), 안전성(Safety), 정밀도(Precision), 운영 마감시간(Operational Deadline) 사이의 균형을 유지해야 한다.

예측 제어(Predictive Control)는 미래의 물리적 요구사항(Future Physical Requirement)을 예상하여 에너지 소비를 줄일 수 있다. 모델 예측 제어(Model Predictive Control, MPC)는 계획 구간(Planning Horizon) 전반에서 가속(Acceleration), 제동(Braking), 액추에이터 출력(Actuator Effort)을 조정할 수 있다. 학습된 동역학 모델(Learned Dynamics Model)은 지형 저항(Terrain Resistance)이나 조작 하중(Manipulation Load)에 대한 예측을 개선할 수 있다. 그러나 부정확한 모델은 비효율적이거나 위험한 행동을 생성할 수 있으므로 불확실성 추정(Uncertainty Estimation)과 피드백 보정(Feedback Correction)이 에너지 인식 제어(Energy-Aware Control)의 필수 요소가 된다.

에너지 하베스팅(Energy Harvesting)과 회생 메커니즘(Regenerative Mechanism)은 일부 응용 분야에서 운영 지속시간(Operational Endurance)을 연장할 수 있다. 회생 제동(Regenerative Braking)은 감속(Deceleration) 과정에서 운동 에너지(Kinetic Energy)의 일부를 회수할 수 있으며, 적절한 기계 시스템(Mechanical System)은 저장된 탄성 에너지(Stored Elastic Energy)를 재사용할 수 있다. 이러한 이점은 액추에이터 아키텍처(Actuator Architecture), 운영 조건(Operating Condition), 변환 손실(Conversion Loss)에 따라 달라진다. 이러한 메커니즘은 에너지 효율적인 지능(Energy-Efficient Intelligence)을 보완하지만 물리적 일(Physical Work)에 의해 결정되는 근본적인 한계(Fundamental Limit)를 제거할 수는 없다.

다중 로봇 시스템(Multi-Robot System)은 에너지 인식 작업 할당(Energy-Aware Task Allocation)의 기회를 제공한다. 배터리 수준(Battery Level), 적재 능력(Payload Capability), 이동 효율(Locomotion Efficiency)이 서로 다른 로봇들은 전체 플릿 에너지 소비(Total Fleet Energy Consumption)를 줄이도록 작업을 분배할 수 있다. 충전 일정(Charging Schedule)과 임무 할당(Mission Assignment)은 이동 거리(Travel Distance), 예상 작업 부하(Expected Workload), 인프라 가용성(Infrastructure Availability)을 고려할 수 있다. 그러나 플릿 에너지 최소화(Fleet Energy Minimization)는 마감시간(Deadline), 통신 신뢰성(Communication Reliability), 운영 복원력(Operational Resilience)과 균형을 이루어야 한다.

장기 자율성(Long-Horizon Autonomy)을 위해서는 로봇이 에너지를 제한된 전략적 자원(Limited Strategic Resource)으로 인식하고 추론해야 한다. 시스템은 임무를 완료하고, 외란(Disturbance)으로부터 복구하며, 충전 위치(Charging Location)에 도달할 수 있는 충분한 용량이 남아 있는지 판단해야 한다. 에너지 예비량(Energy Reserve)은 이동 시간(Travel Time)과 물리적 작업 부하(Physical Workload)에 관한 불확실성을 반영해야 한다. 따라서 신뢰할 수 있는 임무 계획(Reliable Mission Planning)은 에너지 예측(Energy Prediction)을 안전 여유도(Safety Margin) 및 비상 대응 전략(Contingency Strategy)과 통합해야 한다.

지속 학습(Continual Learning)은 축적된 운영 경험(Accumulated Operational Experience)을 통해 에너지 효율성을 개선할 수 있다. 로봇은 반복적으로 발생하는 불필요한 움직임(Wasted Movement), 비효율적인 파지 전략(Inefficient Grasp Strategy), 불필요한 연산(Unnecessary Computation)의 원인을 발견할 수 있다. 플릿 데이터(Fleet Data)는 서로 다른 환경(Environment)과 적재 조건(Payload Condition)에 대한 에너지 모델(Energy Model)의 업데이트를 지원할 수 있다. 그러나 이러한 개선은 변화하는 하드웨어 특성(Hardware Characteristic)과 에너지 소비 감소가 다른 성능 목표(Performance Objective)를 훼손할 가능성을 고려하여 검증되어야 한다.

에너지 효율적인 피지컬 인공지능(Energy-Efficient Physical AI)의 평가는 작업 수준 에너지 소비(Task-Level Energy Consumption), 운영 지속시간(Operational Endurance), 계산 전력(Computational Power), 액추에이터 효율(Actuator Efficiency), 열적 안정성(Thermal Stability)을 포함해야 한다. 비교 평가(Comparative Evaluation)에서는 작업 난이도(Task Difficulty), 적재 하중(Payload), 환경(Environment), 하드웨어 구성(Hardware Configuration)을 통제해야 한다. 에너지 측정(Energy Measurement)은 순간 전력(Instantaneous Power)과 총에너지 소비(Total Energy Expenditure)를 구분해야 한다. 표준화된 평가(Standardized Evaluation)가 없다면 겉으로 드러나는 개선은 실제 지능 향상(Genuine Intelligence Gain)이 아니라 유리한 시험 조건(Favorable Testing Condition)을 반영할 수 있다.

주요 미해결 연구 질문(Open Research Question)은 지능 복잡성(Intelligence Complexity)과 물리적 에너지 절감(Physical Energy Saving) 사이의 관계에 관한 것이다. 더 높은 능력을 갖춘 모델(More Capable Model)은 추가적인 계산 에너지(Computational Energy)를 소비하면서도 더 짧은 궤적(Shorter Trajectory), 적은 실패(Fewer Failure), 더 나은 작업 협조(Task Coordination)를 구현할 수 있다. 소형 모델(Smaller Model)은 추론 과정에서는 효율적이지만 더 많은 보정 행동(Corrective Action)을 요구할 수 있다. 최적의 균형(Optimal Balance)을 결정하려면 추론 품질(Reasoning Quality)과 물리적 실행 비용(Physical Execution Cost)을 연결하는 시스템 수준 측정(System-Level Measurement)이 필요하다.

또 다른 과제는 여러 시간 척도(Multiple Timescale)에 걸쳐 에너지 소비를 적응적으로 조절하는 아키텍처(Architecture)를 개발하는 것이다. 밀리초 수준 제어(Millisecond-Level Control)는 예측 가능한 응답성(Predictable Responsiveness)을 요구하는 반면, 임무 계획(Mission Planning)은 수분 또는 수시간에 걸쳐 작업 부하(Workload)를 조정할 수 있다. 배터리 관리(Battery Management)는 충전 주기(Charging Cycle)와 성능 저하(Degradation)를 포함하는 더 긴 시간 범위에서 작동한다. 이러한 시간 척도를 조정하려면 공유 에너지 제약(Shared Energy Constraint)을 관리하면서 안전성과 성능을 유지하는 계층적 지능(Hierarchical Intelligence)이 필요하다.

궁극적으로 에너지 효율적인 물리 지능(Energy-Efficient Physical Intelligence)을 구현하려면 연산(Computation), 신체 구현(Embodiment), 센싱(Sensing), 구동(Actuation), 임무 계획(Mission Planning)을 통합된 에너지 시스템(Unified Energy System)의 구성 요소로 다루어야 한다. 발전은 적응형 추론(Adaptive Inference), 효율적인 형태(Efficient Morphology), 예측 제어(Predictive Control), 신뢰할 수 있는 에너지 추정(Reliable Energy Estimation), 시스템 수준 최적화(System-Level Optimization)에 달려 있다. 장기적인 목표는 안전하고 지속적인 운영(Safe and Sustained Operation)에 필요한 에너지를 최소화하면서 점점 더 높은 수준의 물리적 행동 능력(Physical Behavioral Capability)을 제공하는 자율 지능(Autonomous Intelligence)을 구현하는 것이다.

## 07.16. Multi Robot Collective Intelligence

![](images/image16.png){width="7.268055555555556in" height="7.268055555555556in"}

다중 로봇 집단 지능(Multi-Robot Collective Intelligence)은 여러 로봇이 협력하여 개별 기계의 능력을 넘어서는 작업을 수행할 수 있다는 점에서 피지컬 인공지능(Physical AI)의 주요 연구 분야이다. 로봇은 고립된 자율 에이전트(Autonomous Agent)로 작동하는 대신 정보를 공유하고, 책임을 분담하며, 집단 목표(Collective Objective)에 맞춰 행동을 적응시켜야 한다. 핵심 과제는 여러 독립적인 시스템(Independent System)을 신뢰할 수 있고, 협조적이며, 적응 가능한 물리 지능(Physical Intelligence)으로 전환하는 것이다.

집단 지능(Collective Intelligence)은 상호작용(Interaction)과 공유 학습(Shared Learning)을 통해 나타나는 능력을 강조한다는 점에서 기존의 다중 로봇 협조(Multi-Robot Coordination)와 구별된다. 로봇 플릿(Robot Fleet)은 환경을 공동으로 탐색하고, 지도를 구축하며, 대형 객체를 조작하거나, 변화하는 운영 요구(Operational Demand)에 대응할 수 있다. 효과적인 협력(Effective Cooperation)을 위해서는 단순히 움직임을 동기화하는 것 이상이 필요하다. 로봇은 개별 관측(Individual Observation)과 의사결정(Decision-Making)을 전체 임무 성능(Overall Mission Performance)을 향상시키는 일관된 행동(Coherent Behavior)으로 통합해야 한다.

분산 인식(Distributed Perception)은 로봇이 여러 관측 시점(Viewpoint)과 센서 구성(Sensor Configuration)에서 얻은 정보를 바탕으로 환경 이해(Environmental Understanding)를 구축하도록 한다. 한 로봇은 다른 로봇에게 가려진 장애물(Obstacle)을 관측할 수 있으며, 공중 플랫폼(Aerial Platform)과 지상 플랫폼(Ground Platform)은 상호 보완적인 공간 정보(Spatial Information)를 제공할 수 있다. 이러한 관측을 결합하면 상황 인식(Situational Awareness)을 향상시키고 불확실성(Uncertainty)을 줄일 수 있다. 그러나 일치하지 않는 보정(Calibration), 관측 지연(Observation Delay), 상충하는 측정값(Conflicting Measurement)은 신뢰할 수 있는 센서 융합(Sensor Fusion)을 어렵게 만든다.

공유 월드 모델(Shared World Model)은 로봇 팀(Robot Team) 전반의 집단 추론(Collective Reasoning)을 위한 기반을 제공한다. 각 로봇은 객체(Object), 지형(Terrain), 동적 에이전트(Dynamic Agent), 운영 제약(Operational Constraint)에 대한 로컬 표현(Local Representation)을 유지할 수 있다. 집단 지능을 구현하려면 이러한 표현을 충분히 일관된 공유 지식(Shared Knowledge)으로 조정해야 한다. 통신(Communication)이 간헐적으로 이루어지거나, 환경이 빠르게 변화하거나, 개별 로봇의 센싱 능력(Sensing Capability)이 서로 다른 경우 유용한 월드 모델을 유지하기가 어려워진다.

분산 지도 작성 및 위치 추정(Distributed Mapping and Localization)은 집단적 환경 이해(Collective Environmental Understanding)의 어려움을 보여준다. 여러 로봇은 서로 다른 영역을 동시에 담당하여 탐색(Exploration)과 지도 구축(Map Construction)을 가속할 수 있다. 각 로봇의 로컬 지도(Local Map)는 공통 관측(Common Observation), 상대 측정(Relative Measurement), 공유 랜드마크(Shared Landmark)를 통해 최종적으로 정렬되어야 한다. 좌표 변환(Coordinate Transformation)과 루프 폐쇄(Loop Closure)에서 발생한 오류는 팀 전체로 전파될 수 있으므로 불확실성 인식 지도 융합(Uncertainty-Aware Map Fusion)이 필수적이다.

다중 로봇 작업 할당(Multi-Robot Task Allocation)은 집단 목표(Collective Objective)를 사용 가능한 에이전트(Available Agent) 사이에 어떻게 분배할지 결정한다. 작업 할당(Assignment)은 로봇의 능력(Capability), 위치(Location), 에너지 예비량(Energy Reserve), 적재 한계(Payload Limit), 작업 우선순위(Task Priority)에 따라 달라질 수 있다. 중앙집중식 최적화(Centralized Optimization)는 신뢰할 수 있는 통신이 가능한 경우 협조된 계획(Coordinated Plan)을 생성할 수 있다. 분산형 접근법(Distributed Approach)은 더 높은 복원력(Resilience)을 제공할 수 있지만, 지속적인 중앙 감독(Central Supervision) 없이 상충하는 작업 할당과 변화하는 자원 가용성(Resource Availability)을 해결해야 한다.

집단 계획(Collective Planning)은 물리적 행동(Physical Action)의 실행 시점(Timing)과 의존 관계(Dependency)를 조정함으로써 작업 할당을 확장한다. 한 로봇이 자재를 운반하는 동안 다른 로봇은 작업 공간(Workspace)을 준비하고, 세 번째 로봇은 완료 여부를 검증할 수 있다. 이러한 작업 흐름(Workflow)에는 선후 관계(Precedence), 공유 자원(Shared Resource), 운영 제약(Operational Constraint)에 대한 명시적인 표현(Explicit Representation)이 필요하다. 지연(Delay), 실패(Failure), 예상하지 못한 환경 변화(Environmental Change)는 이전에 합의된 일정(Schedule)을 무효화할 수 있으므로 계획은 적응성을 유지해야 한다.

통신(Communication)은 집단 지능(Collective Intelligence)의 근본적인 제약 요소이다. 무선 네트워크(Wireless Network)는 제한된 대역폭(Limited Bandwidth), 가변 지연시간(Variable Latency), 패킷 손실(Packet Loss), 간헐적인 연결 끊김(Disconnection)을 발생시킨다. 대규모 플릿(Large Fleet)에서는 원시 센서 데이터(Raw Sensor Data)를 지속적으로 전송하는 것이 비현실적일 수 있다. 효율적인 협력을 위해서는 네트워크 자원(Network Resource)에 과도한 부담을 주지 않으면서 의사결정 관련 정보(Decision-Relevant Information)를 보존하는 선택적 정보 교환(Selective Information Exchange), 이벤트 기반 통신(Event-Driven Communication), 압축된 공유 표현(Compact Shared Representation)이 필요하다.

탈중앙화 의사결정(Decentralized Decision-Making)은 중앙 조정기(Central Coordinator)와의 통신이 불가능해지더라도 로봇이 유용한 자율성(Autonomy)을 유지하도록 한다. 로컬 에이전트(Local Agent)는 부분적인 정보(Partial Information)를 사용하여 책임을 협상하고, 충돌을 방지하며, 승인된 작업(Authorized Task)을 계속 수행할 수 있다. 그러나 독립적인 의사결정은 일관되지 않은 계획(Inconsistent Plan)이나 안전하지 않은 상호작용(Unsafe Interaction)을 초래할 수 있다. 불완전한 통신(Incomplete Communication) 환경에서도 협조 상태를 유지하는 분산 정책(Distributed Policy)을 설계하는 것은 핵심적인 미해결 과제이다.

합의 메커니즘(Consensus Mechanism)은 로봇 팀이 공유 추정값(Shared Estimate), 작업 우선순위(Task Priority), 협조 행동(Coordinated Action)에 대해 합의하도록 지원할 수 있다. 분산 최적화(Distributed Optimization)와 합의 프로토콜(Agreement Protocol)은 로컬 정보(Local Information)를 결합하기 위한 수학적 도구(Mathematical Tool)를 제공한다. 이러한 방법의 효과는 네트워크 연결성(Network Connectivity), 메시지 전달 시점(Message Timing), 참여 에이전트(Participating Agent)에 관한 가정에 달려 있다. 합의 자체가 합의된 정보의 정확성(Accuracy)이나 그 결과로 나타나는 집단 행동(Collective Behavior)의 안전성을 보장하지는 않는다.

이기종 로봇 팀(Heterogeneous Robot Team)은 상호 보완적인 지능(Complementary Intelligence)을 구현할 기회를 제공한다. 바퀴형 로봇(Wheeled Robot)은 효율적인 운송(Transportation)을 수행하고, 사족 보행 로봇(Quadruped Robot)은 험난한 지형(Difficult Terrain)을 이동하며, 드론(Drone)은 신속한 공중 관측(Aerial Observation)을 수행할 수 있다. 이들의 결합된 능력(Combined Capability)은 동종 로봇 플릿(Homogeneous Fleet)의 능력을 넘어설 수 있다. 그러나 이동성(Mobility), 센싱(Sensing), 제어 인터페이스(Control Interface), 계산 자원(Computational Resource)의 차이로 인해 공통 작업 추상화(Common Task Abstraction)와 신체 특성 인식 협조 메커니즘(Embodiment-Aware Coordination Mechanism)이 필요하다.

집단 학습(Collective Learning)은 로봇이 플릿의 다른 구성원으로부터 획득한 경험(Experience)을 활용하도록 한다. 성공적인 내비게이션 전략(Navigation Strategy), 조작 결과(Manipulation Outcome), 실패 사례(Failure Case)는 공유 훈련 과정(Shared Training Process)에 기여할 수 있다. 연합학습(Federated Learning)은 모든 로컬 데이터(Local Data)를 전송하지 않고도 지식 교환(Knowledge Exchange)을 지원할 수 있다. 그러나 하드웨어(Hardware), 환경 조건(Environmental Condition), 데이터 품질(Data Quality)의 차이로 인해 공유 업데이트(Shared Update)가 특정 로봇의 성능을 저하시킬 수 있다.

창발적 협조(Emergent Coordination)는 집단 지능을 이해하는 또 다른 관점을 제공한다. 단순한 로컬 상호작용 규칙(Local Interaction Rule)은 명시적인 전역 계획(Global Planning) 없이도 조직화된 집단 행동(Organized Group Behavior)을 만들어낼 수 있다. 군집 로보틱스(Swarm Robotics)는 로컬 신호 전달(Local Signaling)과 분산 적응(Distributed Adaptation)을 포함하여 생물학적 집단(Biological Collective)에서 영감을 얻은 메커니즘을 탐구한다. 창발성(Emergence)은 확장성(Scalability)을 향상시킬 수 있지만, 안전 필수 요구사항(Safety-Critical Requirement)을 충족해야 하는 경우 복잡한 행동을 예측하고, 검증하고, 제어하기는 여전히 어렵다.

집단 지능(Collective Intelligence)은 다른 로봇에 관한 불확실성(Uncertainty)을 관리하는 능력도 요구한다. 하나의 에이전트(Agent)는 팀원이 작업 할당(Assignment)을 완료했는지, 장애물(Obstacle)을 만났는지, 예정된 경로(Intended Route)를 변경했는지 알지 못할 수 있다. 공유 신념 표현(Shared Belief Representation)과 확률적 협조(Probabilistic Coordination)는 불완전한 정보(Incomplete Information)를 관리하는 데 도움이 될 수 있다. 그러나 불확실성이 작업 의존 관계(Task Dependency)를 따라 전파될 수 있으므로 장시간 임무(Long-Duration Mission)에서 신뢰할 수 있는 협력(Reliable Cooperation)을 유지하기는 어렵다.

다중 로봇 시스템(Multi-Robot System)의 안전성(Safety)은 개별 로봇의 충돌 회피(Individual Collision Avoidance)를 넘어선다. 로봇들은 공유 작업 공간(Shared Workspace)에서 서로 간섭하거나, 비상 경로(Emergency Route)를 차단하거나, 동시 행동(Simultaneous Action)을 통해 위험한 상호작용(Hazardous Interaction)을 발생시킬 수 있다. 집단 안전(Collective Safety)을 위해서는 공간적 분리(Spatial Separation), 자원 접근(Resource Access), 비상 대응(Emergency Response)의 조정이 필요하다. 독립적인 안전 제어기(Independent Safety Controller)는 팀 수준 계획(Team-Level Planning)을 보완하여 집단 추론(Collective Reasoning)이 실패하더라도 로컬 보호(Local Protection)가 유지되도록 해야 한다.

결함 허용성(Fault Tolerance)은 대규모 플릿(Large Fleet)에서 하드웨어 고장(Hardware Failure), 통신 장애(Communication Disruption), 소프트웨어 오류(Software Error)가 불가피하게 발생한다는 점에서 필수적이다. 집단 시스템(Collective System)은 사용 불가능한 에이전트(Unavailable Agent)를 탐지하고, 미완료 작업(Unfinished Task)을 재분배하며, 필수 임무 기능(Essential Mission Function)을 유지해야 한다. 중복성(Redundancy)은 복원력(Resilience)을 향상시킬 수 있지만 자원 비용(Resource Cost)도 증가시킨다. 핵심 과제는 개별 고장이 시스템 전체의 장애(System-Wide Disruption)로 전파되는 것을 방지하고 점진적 성능 저하(Graceful Degradation)를 구현하는 것이다.

확장성(Scalability)은 로봇 수가 소규모 팀(Small Team)에서 수백 대의 자율 에이전트(Autonomous Agent)로 증가함에 따라 새로운 어려움을 발생시킨다. 중앙집중식 연산(Centralized Computation)과 통신은 병목 현상(Bottleneck)을 일으킬 수 있으며, 완전히 탈중앙화된 협조(Fully Decentralized Coordination)는 과도한 협상 오버헤드(Negotiation Overhead)를 발생시킬 수 있다. 계층적 아키텍처(Hierarchical Architecture)는 로컬 자율성(Local Autonomy)을 지역 수준 및 임무 수준 오케스트레이션(Regional and Mission-Level Orchestration)과 결합할 수 있다. 그 효과는 응답성(Responsiveness)과 운영 일관성(Operational Consistency)을 희생하지 않으면서 권한(Authority)을 배분하는 방식에 달려 있다.

인간 감독(Human Supervision)은 집단 로봇 운영(Collective Robotic Operation)에서 여전히 중요하다. 운영자(Operator)는 플릿 상태(Fleet Status), 임무 진행 상황(Mission Progress), 불확실성(Uncertainty), 새롭게 발생하는 충돌 상황(Emerging Conflict)을 이해할 수 있는 표현(Representation)이 필요하다. 플릿 규모가 증가하면 개별 행동(Individual Action)을 감독하는 것은 비현실적이 된다. 따라서 인간-기계 인터페이스(Human-Machine Interface)는 확장 가능한 운영에 필요한 자율성을 유지하면서 임무 수준 개입(Mission-Level Intervention), 예외 처리(Exception Handling), 명확한 책임 경계(Responsibility Boundary)를 지원해야 한다.

에너지 인식 집단 지능(Energy-Aware Collective Intelligence)은 개별 배터리 소비(Individual Battery Consumption)만 최적화하는 대신 전체 로봇 팀(Robot Team)의 자원을 고려한다. 작업 할당(Task Allocation)은 충전 가용성(Charging Availability), 이동 거리(Travel Distance), 이동 효율(Locomotion Efficiency)의 차이를 반영할 수 있다. 로봇들은 임무 수행 범위(Mission Coverage)를 유지하기 위해 충전 일정(Charging Schedule)을 조정할 수 있다. 그러나 로컬 에너지 절약 결정(Local Energy-Saving Decision)이 집단 생산성(Collective Productivity)을 감소시킬 수 있으므로 플릿 전체 목표(Fleet-Wide Objective)에 대한 최적화가 필요하다.

집단 지능(Collective Intelligence)의 평가는 로봇 수(Number of Robots)나 완료된 작업(Completed Task)의 수를 측정하는 수준을 넘어야 한다. 관련 평가 지표(Evaluation Metric)에는 임무 성공(Mission Success), 협조 오버헤드(Coordination Overhead), 통신 효율(Communication Efficiency), 결함 복구(Fault Recovery), 안전성(Safety), 확장성(Scalability)이 포함된다. 실험에서는 집단 성능(Collective Performance)을 적절한 독립 에이전트 기준선(Independent-Agent Baseline)과 비교해야 한다. 진정으로 지능적인 집단(Intelligent Collective)은 협력에 따른 추가적인 복잡성(Additional Complexity)을 정당화할 수 있는 이점을 입증해야 한다.

주요 미해결 연구 질문(Open Research Question)은 서로 다른 로봇 신체 구현(Robot Embodiment)과 운영 환경(Operating Environment) 전반에서 공유 지능(Shared Intelligence)을 어떻게 표현해야 하는가에 관한 것이다. 상위 수준의 목표(High-Level Goal)와 의미론적 지식(Semantic Knowledge)은 비교적 쉽게 전이될 수 있지만, 물리적 기술(Physical Skill)은 플랫폼 특화(Platform-Specific) 특성을 유지하는 경우가 많다. 작업(Task), 능력(Capability), 환경 제약(Environmental Constraint)에 대한 재사용 가능한 표현(Reusable Representation)을 개발하면 더 폭넓은 협력을 지원할 수 있다. 이러한 표현은 각 로봇의 실제 물리적 능력(Actual Physical Ability)에 기반해야 한다.

또 다른 미해결 과제(Unresolved Challenge)는 동적으로 변화하는 구성원(Dynamic Membership)과 불확실한 통신(Uncertain Communication) 환경에서 신뢰할 수 있는 집단 행동(Dependable Collective Behavior)을 확립하는 것이다. 로봇은 임무 수행 중 팀에 합류하거나, 이탈하거나, 고장 나거나, 일시적으로 연결이 끊길 수 있다. 협조 프로토콜(Coordination Protocol)은 전체 운영 계획(Operational Plan)을 반복적으로 재구성하지 않고도 이러한 변화를 수용해야 한다. 신뢰할 수 있는 집단 지능을 위해서는 적응 가능한 조직 구조(Adaptable Organization), 일관된 안전 제약(Consistent Safety Constraint), 공유 의사결정(Shared Decision)을 검증하는 메커니즘이 필요하다.

궁극적으로 다중 로봇 집단 지능(Multi-Robot Collective Intelligence)은 자율 로봇 플릿(Autonomous Robot Fleet)을 공유 인식(Shared Perception), 분산 추론(Distributed Reasoning), 협력 행동(Cooperative Action), 누적 학습(Cumulative Learning)이 가능한 협조적 물리 시스템(Coordinated Physical System)으로 전환하는 것을 목표로 한다. 발전은 확장 가능한 통신(Scalable Communication), 공유 월드 모델(Shared World Model), 이기종 로봇 협조(Heterogeneous Coordination), 결함 허용성(Fault Tolerance), 집단 안전(Collective Safety)에 달려 있다. 장기적인 목표는 개별 로봇의 자율성(Autonomy)과 책임성(Accountability)을 유지하면서 협력을 통해 발현되는 신뢰할 수 있는 지능(Reliable Intelligence)을 구현하는 것이다.

## 07.17. Evaluation of General Physical Intelligence

![](images/image17.png){width="7.268055555555556in" height="7.268055555555556in"}

범용 물리 지능(General Physical Intelligence)의 평가는 로봇의 역량(Robotic Competence)을 사전에 정의된 소수의 작업(Predefined Task)에 대한 성공만으로 충분히 표현할 수 없다는 점에서 피지컬 인공지능(Physical AI)의 근본적인 과제이다. 로봇은 통제된 환경(Controlled Environment)에서 매우 뛰어난 성능을 발휘하더라도 객체(Object), 목표(Objective), 물리적 조건(Physical Condition)이 변화하면 실패할 수 있다. 의미 있는 평가(Meaningful Evaluation)는 안전성(Safety)과 신뢰성(Reliability)을 유지하면서 지능이 작업(Task), 환경(Environment), 신체 구현(Embodiment) 전반으로 전이되는지 판단해야 한다.

범용 물리 지능(General Physical Intelligence)은 다양한 물리적 상황(Physical Situation)에서 인식(Perception), 추론(Reasoning), 학습(Learning), 계획(Planning), 행동(Action)을 수행하는 능력을 포함한다. 따라서 평가는 협소한 작업 전문화(Narrow Task Specialization)와 전이 가능한 역량(Transferable Competence)을 구분해야 한다. 익숙한 조작(Manipulation)이나 내비게이션(Navigation) 벤치마크에서 높은 성능을 보인다고 해서 반드시 폭넓은 지능(Broad Intelligence)을 의미하지는 않는다. 포괄적인 평가 프레임워크(Comprehensive Evaluation Framework)는 광범위한 작업별 재훈련(Task-Specific Retraining) 없이 익숙하지 않은 목표(Unfamiliar Objective)를 얼마나 효과적으로 처리하는지 검토해야 한다.

작업 다양성(Task Diversity)은 범용성(Generality)을 평가하기 위한 핵심 요구사항이다. 벤치마크 모음(Benchmark Suite)에는 내비게이션(Navigation), 조작(Manipulation), 보행(Locomotion), 도구 사용(Tool Use), 검사(Inspection), 협력 작업(Cooperative Operation)이 포함되어야 한다. 작업은 복잡성(Complexity), 지속시간(Duration), 물리적 제약(Physical Constraint), 요구되는 추론 수준(Required Reasoning)에 따라 다양하게 구성되어야 한다. 이러한 영역 전반의 성능은 시스템이 재사용 가능한 능력(Reusable Capability)을 보유하고 있는지, 아니면 개별 벤치마크 환경(Benchmark Environment)에 특화된 해결책(Specialized Solution)에 주로 의존하는지 보여줄 수 있다.

환경 다양성(Environmental Diversity) 역시 물리 지능(Physical Intelligence)이 변화하는 실제 세계 조건(Real-World Condition)에서도 기능을 유지해야 한다는 점에서 중요하다. 조명(Lighting), 지형(Terrain), 객체 재료(Object Material), 복잡한 배치(Clutter), 날씨(Weather), 인간 활동(Human Activity)은 작업 난이도(Task Difficulty)를 크게 변화시킬 수 있다. 평가는 로봇을 통제된 변형(Controlled Variation)과 이전에 경험하지 못한 조건 조합(Unseen Combination of Conditions)에 노출해야 한다. 강건한 일반화(Robust Generalization)를 위해서는 익숙한 훈련 환경(Training Environment) 주변의 작은 교란(Minor Perturbation)을 견디는 것 이상의 능력이 필요하다.

신체 구현 다양성(Embodiment Diversity)은 공정한 평가(Fair Evaluation)에 추가적인 어려움을 발생시킨다. 바퀴형 로봇(Wheeled Robot), 사족 보행 로봇(Quadruped Robot), 휴머노이드(Humanoid), 이동형 매니퓰레이터(Mobile Manipulator)는 서로 다른 물리적 능력(Physical Capability)과 한계(Limitation)를 갖는다. 동일한 작업이라도 우수한 지능보다는 특정 기계적 구성(Mechanical Configuration)에 유리할 수 있다. 평가 프레임워크(Evaluation Framework)는 각 플랫폼의 실현 가능한 행동 공간(Achievable Action Space)을 존중하면서 신체 특화 성능(Embodiment-Specific Performance)과 전이 가능한 추론 및 적응(Transferable Reasoning and Adaptation)을 구분해야 한다.

일반화 시험(Generalization Testing)을 위해서는 훈련 경험(Training Experience)과 평가 시나리오(Evaluation Scenario)를 엄격하게 분리해야 한다. 익숙한 객체(Object), 공간 배치(Layout), 궤적(Trajectory), 시뮬레이션 자산(Simulation Asset)을 재사용하면 능력에 대한 잘못된 추정(Misleading Capability Estimate)이 발생할 수 있다. 비공개 시험 환경(Hidden Test Environment)과 독립적으로 생성된 작업(Independently Generated Task)은 벤치마크 과적합(Benchmark Overfitting)을 줄일 수 있다. 그러나 대규모 파운데이션 모델(Foundation Model)이 광범위한 공개 데이터셋(Public Dataset)과 시뮬레이션 환경을 경험한 경우 데이터 누출(Data Leakage)을 방지하기가 어려워진다.

조합적 일반화(Compositional Generalization)는 로봇이 이전에 학습한 기술(Learned Skill)을 결합하여 익숙하지 않은 문제(Unfamiliar Problem)를 해결할 수 있는지 측정한다. 로봇은 파지(Grasping), 내비게이션(Navigation), 객체 배치(Object Placement)를 개별적으로 이해하더라도 새로운 작업 흐름(Workflow)에서 이를 조정하는 데 어려움을 겪을 수 있다. 평가에는 기존 능력(Known Capability)의 새로운 조합(Novel Combination)을 요구하는 작업이 포함되어야 한다. 성공적인 조합(Successful Composition)은 익숙한 개별 행동을 반복적으로 실행하는 것보다 범용 지능(General Intelligence)에 대한 더 강한 증거를 제공한다.

장기 구간 평가(Long-Horizon Evaluation)는 로봇이 상호 의존적인 행동(Dependent Action)의 긴 연속 과정에서 일관된 행동(Coherent Behavior)을 유지할 수 있는지 검토한다. 복잡한 임무(Complex Mission)에는 기억(Memory), 계획(Planning), 오류 복구(Error Recovery), 중간 결과(Intermediate Outcome)에 대한 적응(Adaptation)이 필요하다. 작은 실행 오류(Execution Error)가 누적되어 후속 단계를 무효화할 수 있다. 따라서 평가 지표(Metric)는 개별 행동 정확도(Isolated Action Accuracy)만 측정하는 대신 전체 임무 성공(Complete Mission Success), 복구 효과(Recovery Effectiveness), 계획 수정 능력(Plan Revision Capability)을 고려해야 한다.

물리적 추론(Physical Reasoning)은 기하학(Geometry), 접촉(Contact), 힘(Force), 안정성(Stability), 재료 특성(Material Property)이 관련된 상호작용을 통해 평가되어야 한다. 로봇은 객체가 미끄러질지, 구조물이 하중(Load)을 지탱할 수 있을지, 익숙하지 않은 도구(Unfamiliar Tool)를 어떻게 사용해야 할지 예측해야 할 수 있다. 이러한 시험은 실제 물리적 이해(Genuine Physical Understanding)와 암기된 시각적 패턴(Memorized Visual Pattern)을 구분해야 한다. 반사실적 질문(Counterfactual Question)과 통제된 물리적 개입(Controlled Physical Intervention)은 추가적인 증거를 제공할 수 있다.

적응 속도(Adaptation Speed)는 범용 물리 지능(General Physical Intelligence)의 중요한 지표이다. 높은 역량을 갖춘 로봇(Capable Robot)은 익숙하지 않은 객체(Unfamiliar Object), 변화하는 동역학(Changing Dynamics), 새로운 작업 지시(New Task Instruction)를 접했을 때 행동을 개선해야 한다. 평가는 허용 가능한 성능(Acceptable Performance)에 도달하는 데 필요한 시연(Demonstration), 상호작용(Interaction), 훈련 업데이트(Training Update)의 수를 측정할 수 있다. 샘플 효율성(Sample Efficiency)은 적응 과정에서 소비되는 물리적 위험(Physical Risk)과 계산 자원(Computational Resource)도 함께 고려하여 평가해야 한다.

불확실성 인식(Uncertainty Awareness)과 의사결정 신뢰성(Decision Reliability)은 범용 지능 평가(General Intelligence Assessment)에 포함되어야 한다. 로봇은 모호한 관측(Ambiguous Observation), 신뢰할 수 없는 예측(Unreliable Prediction), 자신의 역량 범위를 벗어나는 조건(Condition Beyond Competence)을 인식해야 한다. 적절한 대응에는 추가 센싱(Additional Sensing), 신중한 행동(Cautious Action), 지원 요청(Assistance Request), 안전한 종료(Safe Termination)가 포함될 수 있다. 평가는 불확실성과 관계없이 작업 완료만 보상하는 대신 신뢰도 보정(Confidence Calibration)과 위험 민감형 행동(Risk-Sensitive Behavior)을 측정해야 한다.

안전성 평가(Safety Evaluation)는 일상적인 운영(Routine Operation)과 드물게 발생하는 위험 조건(Rare Hazardous Condition)을 모두 다루어야 한다. 충돌 회피(Collision Avoidance), 힘 제한(Force Limit), 인간과의 근접성(Human Proximity), 비상 대응(Emergency Response), 복구 행동(Recovery Behavior)은 다양한 로봇 응용 분야(Robotic Application)에서 중요하다. 안전하지 않은 실험(Unsafe Experimentation)을 통해 높은 작업 성공률(Task Success Rate)을 달성한 시스템은 신뢰할 수 있는 범용 지능(Dependable General Intelligence)을 입증했다고 볼 수 없다. 따라서 위험한 절충 관계(Dangerous Tradeoff)가 감춰지지 않도록 안전성 지표(Safety Metric)는 생산성(Productivity)과 별도로 보고되어야 한다.

학습 효율성(Learning Efficiency)은 계산 및 물리적 자원 소비(Computational and Physical Resource Consumption)와 함께 고려해야 한다. 두 로봇이 유사한 작업 성공률(Task Success Rate)을 달성하더라도 필요한 훈련 데이터(Training Data), 추론 에너지(Inference Energy), 물리적 실험(Physical Experimentation)의 양은 크게 다를 수 있다. 평가에는 학습 비용(Learning Cost), 배포 전력(Deployment Power), 실행 시간(Execution Time), 하드웨어 요구사항(Hardware Requirement)이 반영되어야 한다. 자원 정규화 측정(Resource-Normalized Measurement)은 겉으로 드러나는 지능 향상이 주로 계산 자원 증가(Increased Computational Expenditure)에 의존하는지 밝혀낼 수 있다.

인간과의 상호작용(Human Interaction)은 평가의 또 다른 차원을 제공한다. 범용 로봇(General-Purpose Robot)은 물리적 작업을 수행하는 동안 지시(Instruction)를 해석하고, 모호성(Ambiguity)을 해결하며, 한계(Limitation)를 전달하고, 인간과 협력해야 한다. 지시를 실행 가능한 행동(Feasible Action)에 연결할 수 없다면 언어 이해(Language Understanding)만으로는 충분하지 않다. 평가는 명확화 요청 행동(Clarification Behavior), 공유된 작업 이해(Shared Task Understanding), 인간의 의도(Human Intention)가 변화할 때 안전성을 유지하는 능력을 검토해야 한다.

다중 로봇 평가(Multi-Robot Evaluation)는 집단적 능력(Collective Capability)이 독립적으로 작동하는 에이전트(Independent Agent)의 능력을 넘어서는지 판단해야 한다. 공유 인식(Shared Perception), 협력 계획(Cooperative Planning), 작업 할당(Task Allocation), 협조된 복구(Coordinated Recovery)는 임무 성능(Mission Performance)을 향상시킬 수 있다. 그러나 통신 오버헤드(Communication Overhead)와 협조 실패(Coordination Failure)가 이러한 이점을 상쇄할 수 있다. 적절한 기준선(Baseline)은 비교 가능한 자원(Resource)과 환경 제약(Environmental Constraint) 아래에서 집단 결과(Collective Outcome)를 개별 역량(Individual Capability)과 비교해야 한다.

벤치마크 설계(Benchmark Design)는 표준화(Standardization)와 생태학적 타당성(Ecological Validity) 사이의 균형을 유지해야 한다. 고도로 통제된 시험(Highly Controlled Test)은 재현성(Reproducibility)과 과학적 비교(Scientific Comparison)를 지원하지만 실제 배포(Real Deployment)의 복잡성을 충분히 반영하지 못할 수 있다. 개방형 현장 평가(Open-Ended Field Evaluation)는 현실적인 과제를 제공하지만 통제되지 않은 변수(Uncontrolled Variable)를 도입한다. 표준화된 실험실 벤치마크(Standardized Laboratory Benchmark)와 조건이 신중하게 기록된 실제 세계 시험(Real-World Trial)을 결합하면 비교 가능성(Comparability)과 실용적 관련성(Practical Relevance)을 모두 향상시킬 수 있다.

평가 지표(Evaluation Metric)는 평균 성공률(Average Success Rate)만 보고하는 대신 성능 분포(Performance Distribution)를 포착해야 한다. 최악의 결과(Worst-Case Outcome), 실패 심각도(Failure Severity), 복구 시간(Recovery Time), 환경별 변동성(Variability Across Environments)은 단일 종합 점수(Aggregate Score)보다 더 유익할 수 있다. 물리적 실험(Physical Experiment)에는 상당한 확률적 변동(Stochastic Variation)이 존재하므로 신뢰구간(Confidence Interval)과 반복 시험(Repeated Trial)이 필요하다. 투명한 보고(Transparent Reporting)는 측정된 결과(Measured Result)와 외삽된 능력 주장(Extrapolated Capability Claim)을 구분해야 한다.

아직 해결되지 않은 과제(Unresolved Challenge)는 시스템 간 중요한 차이(Important Difference)를 감추지 않으면서 범용 물리 지능(General Physical Intelligence)의 통합 측정 기준(Unified Measure)을 정의하는 것이다. 복합 점수(Composite Score)는 비교를 단순화할 수 있지만 안전성(Safety), 적응성(Adaptability), 물리적 추론(Physical Reasoning)의 약점을 가릴 수 있다. 다차원 능력 프로파일(Multidimensional Capability Profile)은 더 높은 투명성(Transparency)을 제공하지만 순위 산정(Ranking)을 복잡하게 만든다. 평가 프레임워크(Evaluation Framework)는 어떤 차원(Dimension)이 필수적인지, 그리고 각 차원의 상대적 중요성(Relative Importance)을 어떻게 정당화할지 결정해야 한다.

진전 측정(Progress Measurement)을 위해서는 로봇 능력(Robotic Capability)의 발전에 따라 진화하는 벤치마크(Evolving Benchmark)도 필요하다. 고정된 작업(Static Task)은 결국 성능 포화(Saturation)에 도달하거나 특화된 최적화(Specialized Optimization)에 취약해질 수 있다. 지속적으로 갱신되는 평가(Continually Refreshed Evaluation)는 새로운 객체(Object), 환경(Environment), 목표(Objective), 상호작용 패턴(Interaction Pattern)을 도입할 수 있다. 그러나 벤치마크 변경(Benchmark Change)은 장기적 비교(Longitudinal Comparison)를 어렵게 만든다. 안정적인 참조 작업(Stable Reference Task)과 지속적으로 변화하는 도전 과제 집합(Evolving Challenge Set)을 함께 유지하는 것이 실용적인 절충안이 될 수 있다.

재현성(Reproducibility)은 물리적 결과(Physical Outcome)가 하드웨어 상태(Hardware Condition), 보정(Calibration), 환경 변화(Environmental Variation), 운영자 절차(Operator Procedure)에 의존하기 때문에 여전히 확보하기 어렵다. 두 연구실(Laboratory)은 명목상 동일한 로봇(Robot)과 정책(Policy)을 사용하더라도 서로 다른 결과를 얻을 수 있다. 평가 프로토콜(Evaluation Protocol)은 하드웨어 구성(Hardware Configuration), 소프트웨어 버전(Software Version), 훈련 데이터(Training Data), 실험 조건(Experimental Condition)을 기록해야 한다. 독립적인 재현 검증(Independent Replication)은 신뢰할 수 있는 역량 발전(Reliable Capability Advance)과 일회성 시연(Isolated Demonstration)을 구분하는 데 필수적이다.

또 다른 미해결 질문(Open Question)은 시뮬레이션 평가(Simulated Evaluation)와 실제 세계 지능(Real-World Intelligence) 사이의 관계에 관한 것이다. 시뮬레이션(Simulation)은 드문 사건(Rare Event)과 다양한 환경(Diverse Environment)에 대한 대규모 시험(Large-Scale Testing)을 가능하게 하지만, 모델링 부정확성(Modeling Inaccuracy)을 이용하는 전략에 유리한 평가 결과를 제공할 수 있다. 물리적 시험(Physical Trial)은 더 강한 현실적 근거(Grounding)를 제공하지만 비용이 높고 잠재적으로 위험하다. 신뢰할 수 있는 평가를 위해서는 어떤 시뮬레이션 지표(Simulated Metric)가 실제 배포 성능(Real Deployment Performance)을 예측하는지, 그리고 이러한 상관관계(Correlation)가 어디에서 무너지는지 이해해야 한다.

궁극적으로 범용 물리 지능(General Physical Intelligence)의 평가에는 일반화(Generalization), 추론(Reasoning), 적응(Adaptation), 장기 구간 역량(Long-Horizon Competence), 안전성(Safety), 효율성(Efficiency), 협력(Cooperation)을 포괄하는 다차원 프레임워크(Multidimensional Framework)가 필요하다. 단일 벤치마크(Single Benchmark)만으로는 보편적 로봇 지능(Universal Robotic Intelligence)을 입증할 수 없다. 발전을 위해서는 익숙하지 않은 물리적 조건(Unfamiliar Physical Condition) 전반에 걸친 엄격한 시험(Rigorous Testing), 투명한 결과 보고(Transparent Reporting), 독립적인 검증(Independent Validation)이 필요하다. 목표는 인상적인 행동(Impressive Behavior)의 개별 시연이 아니라 전이 가능하고 신뢰할 수 있는 역량(Transferable, Dependable Competence)을 측정하는 것이다.

## 07.18. Measuring Progress Toward Physical AGI

![](images/image18.png){width="7.268055555555556in" height="7.268055555555556in"}

물리적 범용 인공지능(Physical Artificial General Intelligence, Physical AGI)을 향한 발전을 측정하려면 자율 시스템(Autonomous System)이 개별적인 작업 특화 성과(Task-Specific Achievement)를 축적하는 수준을 넘어 폭넓게 전이 가능한 능력(Broadly Transferable Capability)을 개발하고 있는지 판단해야 한다. Physical AGI는 익숙하지 않은 물리적 상황(Physical Situation) 전반에서 인식(Perception), 추론(Reasoning), 학습(Learning), 행동(Action)을 수행할 수 있는 지능을 의미한다. 따라서 발전 수준은 일반화(Generalization), 적응성(Adaptability), 신뢰성(Reliability), 지속적인 실제 세계 역량(Sustained Real-World Competence)을 통해 평가되어야 한다.

기존 인공지능 벤치마크(Conventional AI Benchmark)와 달리 Physical AGI 평가는 지능(Intelligence)과 신체 구현(Embodiment) 사이의 상호작용(Interaction)을 고려해야 한다. 로봇의 성능은 센서(Sensor), 액추에이터(Actuator), 기계적 구조(Mechanical Structure), 계산 자원(Computational Resource), 운영 환경(Operating Environment)에 따라 달라진다. 우수한 하드웨어(Superior Hardware)는 더 나은 추론 능력(Reasoning Capability)을 입증하지 않더라도 작업 성공률(Task Success Rate)을 높일 수 있다. 의미 있는 발전 측정(Progress Measurement)은 물리적 플랫폼(Physical Platform)의 발전과 전이 가능한 지능(Transferable Intelligence)의 발전을 구분해야 한다.

핵심적인 어려움은 물리적 세계(Physical World)에서 범용성(Generality)이 무엇을 의미하는지 정의하는 것이다. 유한한 작업 집합(Finite Task Set)으로는 가능한 모든 환경(Environment), 객체(Object), 상호작용(Interaction)을 표현할 수 없다. 따라서 평가는 작업 다양성(Task Diversity)과 신규성(Novelty)이 증가함에 따라 성능이 어떻게 변화하는지 검토해야 한다. 더 높은 범용성에 접근하는 시스템은 익숙하지 않은 목표(Goal), 물리적 제약(Physical Constraint), 환경 조건(Environmental Condition)의 조합에서도 안정적인 역량(Stable Competence)을 보여야 한다.

능력의 폭(Capability Breadth)은 발전 측정(Progress Measurement)의 한 가지 차원을 제공한다. Physical AGI 후보 시스템(Candidate System)은 다양한 환경에서 내비게이션(Navigation), 조작(Manipulation), 보행(Locomotion), 도구 사용(Tool Use), 물리적 추론(Physical Reasoning), 인간과의 상호작용(Human Interaction)을 수행할 수 있어야 한다. 그러나 각 능력이 별도로 설계된 해결책(Separately Engineered Solution)에 의존한다면 폭넓은 능력만으로는 충분하지 않다. 더 강력한 증거는 광범위한 아키텍처 수정(Architectural Modification) 없이 여러 작업을 지원하는 공유 표현(Shared Representation)과 정책(Policy)에서 얻을 수 있다.

전이 효율성(Transfer Efficiency)은 또 다른 중요한 지표이다. 시스템은 시뮬레이션(Simulation), 특정 로봇 플랫폼(Robot Platform), 특정 환경(Environment)에서 기술(Skill)을 학습한 후 이를 다른 조건에 적용할 수 있다. 발전 수준은 성공적인 전이(Successful Transfer)에 필요한 추가 데이터(Additional Data), 훈련 시간(Training Time), 물리적 상호작용(Physical Interaction)을 통해 측정할 수 있다. 범용성이 향상될수록 익숙하지 않은 조건에서도 신뢰할 수 있는 성능(Reliable Performance)을 유지하면서 적응 비용(Adaptation Cost)이 감소해야 한다.

새로운 작업 습득(Novel-Task Acquisition)은 진정한 범용 지능(General Intelligence)이 사전에 정의된 시연(Predefined Demonstration)에 전적으로 의존할 수 없다는 점에서 특히 중요하다. 로봇은 익숙하지 않은 목표(Unfamiliar Objective)를 해석하고, 필요한 능력(Required Capability)을 식별하며, 적절한 행동 순서(Action Sequence)를 구성해야 한다. 평가에서는 이전에 경험하지 못한 작업 조합(Unseen Task Combination)을 제시하고 시스템이 유능한 실행(Competent Execution)에 도달하는 속도를 측정할 수 있다. 이러한 시험은 유연한 문제 해결(Flexible Problem Solving)과 암기된 해결책(Memorized Solution)의 검색을 구분해야 한다.

물리적 추론(Physical Reasoning)은 패턴 인식(Pattern Recognition)을 넘어서는 지능의 증거를 제공한다. 로봇은 힘(Force), 접촉(Contact), 기하학(Geometry), 안정성(Stability), 재료 특성(Material Property), 인과적 결과(Causal Consequence) 사이의 관계를 이해해야 한다. 발전 수준은 익숙하지 않은 물리적 상황에서의 예측(Prediction)과 개입(Intervention)을 통해 측정할 수 있다. 시스템은 관측(Observation)이 내부 모델(Internal Model)과 모순될 때 이전에 성공한 행동을 반복하는 대신 잘못된 가정(Incorrect Assumption)을 수정하는 능력을 보여야 한다.

장기 구간 역량(Long-Horizon Competence)은 실용적인 자율성(Practical Autonomy)이 연속적인 행동(Action Sequence) 전반에서 목표(Objective)를 유지해야 한다는 점에서 필수적이다. 로봇은 중간 결과(Intermediate Outcome)를 기억하고, 상호 의존적인 하위 작업(Dependent Subtask)을 조정하며, 예상하지 못한 사건(Unexpected Event)으로부터 복구해야 한다. 개별 행동 정확도(Individual Action Accuracy)만 측정하면 계획(Planning)과 실행(Execution)의 중대한 약점을 감출 수 있다. 임무 수준 성공(Mission-Level Success), 복구 효과(Recovery Effectiveness), 누적 오류(Accumulated Error)는 발전 수준을 판단하는 데 더 유용한 지표를 제공한다.

지속 학습(Continual Learning)은 Physical AGI를 향한 발전을 정의하는 또 다른 핵심 요구사항이다. 자율 시스템(Autonomous System)은 이전에 숙달한 능력(Previously Mastered Capability)을 반복적으로 잊어버리지 않으면서 새로운 지식(New Knowledge)을 습득해야 한다. 평가는 익숙하지 않은 작업을 학습하기 전후의 성능을 검토하고, 지식 유지(Retention)와 간섭 효과(Interference Effect)를 포함해야 한다. 빠른 적응(Rapid Adaptation)을 보여주더라도 심각한 파국적 망각(Catastrophic Forgetting)이 발생하는 시스템은 장기간의 운영 수명(Operational Lifetime) 전반에서 폭넓은 역량을 갖추었다고 볼 수 없다.

월드 모델 품질(World Model Quality)은 물리적 이해(Physical Understanding)를 측정하는 더 심층적인 기준을 제공할 수 있다. 유용한 월드 모델(World Model)은 대안적인 행동(Alternative Action)에 따라 환경이 어떻게 변화하는지 예측하고, 즉각적인 관측(Immediate Observation)을 넘어서는 계획(Planning)을 지원해야 한다. 평가는 익숙하지 않은 상황에서 예측 정확도(Predictive Accuracy), 불확실성 보정(Uncertainty Calibration), 반사실적 추론(Counterfactual Reasoning)을 검토할 수 있다. 그러나 정확한 예측만으로 지능을 입증할 수는 없으며, 모델이 물리적 의사결정(Physical Decision-Making)과 작업 실행(Task Execution)을 개선해야 한다.

신뢰성(Reliability)은 발전 측정(Progress Measurement)의 주요 차원으로 유지되어야 한다. 대부분의 작업을 성공적으로 완료하더라도 간헐적으로 심각한 실패(Severe Failure)를 일으키는 로봇은 자율 배포(Autonomous Deployment)에 적합하지 않을 수 있다. 평가는 성능 분포(Performance Distribution), 희귀 사건 행동(Rare-Event Behavior), 복구 시간(Recovery Time), 실패 심각도(Failure Severity)를 고려해야 한다. Physical AGI를 향한 발전은 평균 벤치마크 점수(Average Benchmark Score)를 극대화하는 데 그치지 않고 위험한 불확실성(Dangerous Uncertainty)을 줄이고 신뢰할 수 있는 행동(Dependable Behavior)을 개선하는 방향으로 이루어져야 한다.

안전성(Safety)과 인간 정렬(Human Alignment)은 물리적 자율성(Physical Autonomy)이 확대될수록 더욱 중요해진다. 로봇은 운영 경계(Operational Boundary)를 인식하고, 인간의 지시(Human Instruction)를 해석하며, 목표(Objective)가 안전 제약(Safety Constraint)과 충돌할 때 적절하게 대응해야 한다. 발전 수준을 측정하려면 개입 요청(Intervention Request), 안전한 대체 행동(Safe Fallback Behavior), 승인된 행동(Authorized Action)의 준수 여부를 평가해야 한다. 높은 자율성(Higher Autonomy)이 인간 감독(Human Oversight)이나 제어 가능성(Controllability)을 감소시킨다면 이를 발전으로 해석해서는 안 된다.

자원 효율성(Resource Efficiency)은 지능 발전(Intelligence Development)을 바라보는 추가적인 관점을 제공한다. 시스템은 더 큰 모델(Larger Model), 더 강력한 프로세서(More Powerful Processor), 광범위한 물리적 실험(Extensive Physical Experimentation)을 사용하여 성능을 향상시킬 수 있다. 이러한 개선은 가치가 있지만 자동으로 더 높은 범용성(Greater Generality)을 의미하지는 않는다. 평가는 훈련 데이터(Training Data), 계산 에너지(Computational Energy), 실행 시간(Execution Time), 물리적 자원(Physical Resource) 대비 작업 성공(Task Success)을 검토하여 실질적으로 더 효율적인 지능(More Efficient Intelligence)을 식별해야 한다.

신체 간 성능(Cross-Embodiment Performance)은 전이 가능한 물리 지능(Transferable Physical Intelligence)을 평가하는 데 특히 유용하다. 서로 다른 매니퓰레이터(Manipulator), 이동 로봇(Mobile Robot), 다족 보행 플랫폼(Legged Platform)을 지원하는 공유 모델(Shared Model)은 작업(Task)과 환경(Environment)에 관한 재사용 가능한 지식(Reusable Knowledge)을 보여줄 수 있다. 그러나 모든 신체 구현(Embodiment)에서 동일한 성능(Identical Performance)을 기대하는 것은 적절하지 않으며 물리적으로도 불가능하다. 발전 수준은 적응 효율성(Adaptation Efficiency)과 각 플랫폼의 능력(Capability)을 적절하게 활용하는 정도를 통해 측정해야 한다.

집단 지능(Collective Intelligence)은 Physical AGI 평가의 범위를 개별 로봇(Individual Robot) 이상으로 확장할 수 있다. 여러 에이전트(Agent)는 관측(Observation)을 공유하고, 복잡한 작업(Complex Task)을 조정하며, 운영 경험(Operational Experience)을 축적할 수 있다. 발전 수준은 협력 추론(Cooperative Reasoning), 분산 계획(Distributed Planning), 결함 복구(Fault Recovery)의 개선을 통해 평가할 수 있다. 그러나 집단적 성공(Collective Success)은 단순히 로봇 수, 통신 인프라(Communication Infrastructure), 계산 자원(Computational Resource)을 추가하여 얻은 성능 향상과 구분되어야 한다.

벤치마크 포화(Benchmark Saturation)는 장기적인 발전 측정(Long-Term Progress Measurement)에 심각한 과제를 제기한다. 시스템은 폭넓게 전이 가능한 능력(Broadly Transferable Ability)을 습득하지 않고도 특화된 최적화(Specialized Optimization)를 통해 높은 점수를 달성할 수 있다. 지속적으로 갱신되는 작업(Continuously Refreshed Task), 비공개 환경(Hidden Environment), 독립 평가(Independent Evaluation)는 이러한 위험을 줄일 수 있다. 안정적인 참조 벤치마크(Stable Reference Benchmark)는 역사적 비교(Historical Comparison)에 여전히 유용하지만, 능력이 발전함에 따라 한계를 드러내기 위해서는 변화하는 도전 과제 집합(Evolving Challenge Set)이 필요하다.

다차원 능력 프로파일(Multidimensional Capability Profile)은 단일 Physical AGI 점수(Single Physical AGI Score)보다 더 유용한 정보를 제공한다. 이러한 프로파일은 일반화(Generalization), 적응 속도(Adaptation Speed), 물리적 추론(Physical Reasoning), 장기 구간 계획(Long-Horizon Planning), 안전성(Safety), 효율성(Efficiency), 지식 유지(Knowledge Retention)를 표현할 수 있다. 복합 지수(Composite Index)는 폭넓은 비교를 지원할 수 있지만 가중치에 관한 가정(Weighting Assumption)을 명시해야 한다. 발전은 보편적 지능(Universal Intelligence)에 대한 근거 없는 주장보다 식별 가능한 개별 차원(Identifiable Dimension)의 개선으로 보고되어야 한다.

종단 평가(Longitudinal Evaluation)는 연속적인 모델 세대(Model Generation)에 걸쳐 개선 효과가 지속되는지 보여줄 수 있다. 연구자는 일관된 평가 프로토콜(Consistent Protocol)을 사용하면서 작업 신규성(Task Novelty)과 난이도(Difficulty)를 통제된 방식으로 증가시켜 시스템을 비교해야 한다. 학습 곡선(Learning Curve), 성능 저하(Performance Degradation), 복구 행동(Recovery Behavior)을 측정하면 의미 있는 추세(Meaningful Trend)를 발견할 수 있다. 개별 시연(Isolated Demonstration)은 안정적으로 일반화되지 않는 능력을 과장할 수 있으므로 독립적인 재현 검증(Independent Replication)이 필수적이다.

시뮬레이션(Simulation)은 다양한 환경(Diverse Environment)과 드문 실패 시나리오(Rare Failure Scenario)를 생성하여 Physical AGI 평가를 가속할 수 있다. 그러나 접촉 동역학(Contact Dynamics), 센서 잡음(Sensor Noise), 환경 복잡성(Environmental Complexity)이 불완전하게 모델링되기 때문에 시뮬레이션 성공(Simulated Success)이 실제 세계 역량(Real-World Competence)으로 직접 이어지지 않을 수 있다. 발전 측정에는 시뮬레이션 기반 스트레스 시험(Simulation-Based Stress Testing)과 물리적 검증(Physical Validation)을 결합해야 한다. 시뮬레이션 점수(Simulated Score)와 실제 배포 결과(Deployment Outcome) 사이의 관계는 실증적으로 확립되어야 한다.

근본적인 미해결 질문(Unresolved Question)은 Physical AGI를 향한 발전이 예측 가능한 스케일링 관계(Predictable Scaling Relationship)를 따르는지에 관한 것이다. 모델 용량(Model Capacity), 훈련 데이터(Training Data), 시뮬레이션 경험(Simulation Experience), 물리적 상호작용(Physical Interaction)을 늘리면 능력이 향상될 수 있지만, 개선 폭은 작업에 따라 크게 달라질 수 있다. 겉으로 나타나는 스케일링 추세(Scaling Trend)는 신체 구현(Embodiment), 인과적 이해(Causal Understanding), 안전성(Safety)의 병목 현상(Bottleneck)을 감출 수 있다. 신뢰할 수 있는 예측(Reliable Forecasting)을 위해서는 계산 규모(Computational Scale)만으로 외삽(Extrapolation)하기보다 이러한 제약을 측정해야 한다.

또 다른 과제는 Physical AGI에 대한 보편적인 임계값(Universal Threshold)을 가정하지 않으면서 의미 있는 이정표(Meaningful Milestone)를 설정하는 것이다. 이정표는 자율성(Autonomy)의 증가, 전이 가능한 기술 습득(Transferable Skill Acquisition), 환경 강건성(Environmental Robustness), 운영 책임(Operational Responsibility)의 확대를 나타낼 수 있다. 각 이정표는 측정 가능한 조건(Measurable Condition)과 인정된 한계(Recognized Limitation)를 명시해야 한다. 이러한 이정표는 범용 물리 지능(General Physical Intelligence)이 단일 수치 점수(Single Numerical Score)에서 갑자기 출현한다는 오해를 피하면서 연구 방향을 제시할 수 있다.

궁극적으로 Physical AGI를 향한 발전을 측정하려면 자율 시스템(Autonomous System)이 익숙하지 않은 물리적 상황(Unfamiliar Physical Situation) 전반에서 더욱 범용적이고(General), 적응 가능하며(Adaptable), 신뢰할 수 있고(Reliable), 효율적인(Efficient) 시스템으로 발전하고 있다는 증거가 필요하다. 개별 벤치마크(Isolated Benchmark), 모델 크기(Model Size), 시연(Demonstration)만으로는 이러한 전환(Transition)을 입증할 수 없다. 가장 강력한 증거는 다양한 작업(Diverse Task) 전반에서의 지속적인 성능(Sustained Performance), 독립적인 검증(Independent Validation), 안전한 실제 세계 운영(Safe Real-World Operation), 재사용 가능한 물리적 지식(Reusable Physical Knowledge)의 축적에서 얻어질 것이다.
