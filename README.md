# Formal Methods for Better Standards: Validating the UML PSSM Standard About State Machine Semantics

My [Scientific Students’ Association (TDK) Report](https://tdk.bme.hu/VIK/sw8/Formalis-modszerekkel-a-jobb-szabvanyokert-Az) co-authored with [Ármin Zavada](https://github.com/zavadaarmin) at Budapest University of Technology and Economics ([BME](https://www.bme.hu/?language=en) [VIK](https://vik.bme.hu/en/) [MIT](https://www.mit.bme.hu/eng/) [ftsrg](https://ftsrg.mit.bme.hu/en/)) under the supervision of [Márton Elekes](https://inf.mit.bme.hu/members/elekesm), [Bence Graics](https://inf.mit.bme.hu/members/graicsb), and [Vince Molnár, PhD](https://inf.mit.bme.hu/members/molnarv). We won **2nd prize** in the [Software section](https://tdk.bme.hu/Browse/VIK/Conferences/TDKVIK2022/Sessions/sw8) of the TDK Conference in 2022.

## Abstract
Humanity is creating more and more complex safety-critical systems, almost all of which are now operated by software. The incorrect operation of these systems can lead to catastrophic consequences, therefore new development principles have become necessary to guarantee safety. One of these principles is model-based systems engineering (MBSE) which has several advantages over traditional ones. 

To apply model-based systems engineering, modeling languages are needed for describing the structure and behavior of systems. The application of executable models is becoming more and more popular in the case of engineering models. The power of executable models lies in their precise execution semantics. In the case of reactive systems, a widely used modeling language is the state machine formalism of the Unified Modeling Language (UML), whose precise semantics is defined in the Precise Semantics of UML State Machines (PSSM) standard. PSSM also presents the expected behavior of such models with a test suite, which defines the possible execution traces of the test models. In terms of the quality of the standard, the consistency of the test suite and the semantics is especially important, as well as demonstrating the possible behaviors completely.

In this work, we formally model the behavior of UML state machines, defined by the PSSM standard, along with the state machines of the test suite. From the resulting models, we automatically generate the possible execution traces using formal methods and compare them with the ones given by the standard.

The presented technique allows the exposure of possible errors and shortcomings in the standard, which, by refining the specification, facilitates the construction of better quality models, and ultimately, the development of safer safety-critical systems as well. The workflow may also serve as an example for developing precise test cases for the modeling languages of the future.

---
Based on the [LaTeX template](https://github.com/ftsrg/thesis-template-latex) of [ftsrg](https://github.com/ftsrg).
