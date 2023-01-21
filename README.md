#  **QPPQ**: *a living review of Quantum Computing + Plasma Physics*

*Quantum Computing promises accelerated simulation of certain classes of problems, in particular in plasma physics. The goal of this document is to provide a comprehensive list of citations for those developing and applying these approaches to experimental or theoretical analyses. As a living document, it will be updated as often as possible to incorporate the latest developments.  Suggestions are most welcome.*

[![download](https://img.shields.io/badge/download-review-blue.svg)](https://QPPQLivingReview.github.io/review/review/QPPQreview.pdf)

The purpose of this note is to collect references for quantum algorithms already relevant to plasma physics.  A minimal number of categories is chosen in order to be as useful as possible. Note that papers may be referenced in more than one category.

To facilitate search, if clearly appropriate, the following tags are applied 

* [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() __noisy-intermediate scale quantum computing__

* [![download](https://img.shields.io/badge/-FTol-red)]() __fault-tolerant quantum computing__

* [![download](https://img.shields.io/badge/-QAnn-blue)]() __quantum annealing__

* [![download](https://img.shields.io/badge/-QIns-grey)]() __quantum-inspired__

Color-filled tags indicate the type of content. Since most papers contain some form of theoretical analysis, we use

* [![download](https://img.shields.io/badge/-Theo-darkred)]() __theoretical__ tag solely for the papers with analytical results, and no considerable numerical or experimental results

* [![download](https://img.shields.io/badge/-Num-darkblue)]() marks papers with __numerical simulations__, but no experimental results run on quantum devices.

* [![download](https://img.shields.io/badge/-Exp-darkgreen)]() marks papers with displayed __experimental__ results. We may ommit this tag if the paper is referenced and tagged in a subsequent subsection.

The fact that a paper is listed in this document does not endorse or validate its content - that is for the community (and for peer-review) to decide.  Furthermore, the classification here is a best attempt and may have flaws - please let us know if (a) we have missed a paper you think should be included, (b) a paper has been misclassified or wrongly tagged, or (c) a citation for a paper is not correct or if the journal information is now available.

In order to be as useful as possible, this document will continue to evolve so please check back. See [http://epp.ist.utl.pt/qppq/](http://epp.ist.utl.pt/qppq/) before you write your next paper. You can simply download the **.bib** file to get all of the latest references. Please consider citing Ref. **\cite{qppqlivingreview}** when referring to this living review.

*  Modern reviews

	*Below are links to (static) general and specialized reviews.*

	* Review of Plasma Physics Problems Reformulated for Quantum Computing [DS20](https://arxiv.org/abs/2005.14369)
	* Review of Fusion Plasma Physics Problems Reformulated for Quantum Computing [Jos+22](https://arxiv.org/abs/2212.05054)
 
*  System of linear equations  [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Num-darkblue)]()  [HBR19](https://arxiv.org/abs/1909.07344) [![download](https://img.shields.io/badge/-Exp-darkgreen)]() [Bra+20](https://arxiv.org/abs/1909.05820)  [Xu+21](https://www.sciencedirect.com/science/article/pii/S2095927321004631) [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [HHL09](https://doi.org/10.1103/PhysRevLett.103.150502) [CJS13](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.110.250504) [CKS17](https://epubs.siam.org/doi/10.1137/16M1087072) [WX22](https://arxiv.org/abs/2208.06763) [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Exp-darkgreen)]() [BL22](https://arxiv.org/abs/2206.10576) [![download](https://img.shields.io/badge/-QIns-grey)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [SM21](https://arxiv.org/abs/2103.10309)
  
*  System of nonlinear equations [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [DS21](https://arxiv.org/abs/2105.07317) [![download](https://img.shields.io/badge/-Num-darkblue)]() [XWG21](https://www.worldscientific.com/doi/10.1142/S201032472140004X) [Xue+22](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.106.032427)

	* System of polynomial equations [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Exp-darkgreen)]() [Cha+19](https://www.nature.com/articles/s41598-019-46729-0)
	
* Ordinary differential equations [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Exp-darkgreen)]()  [Zan+21](https://doi.org/10.22331/q-2021-07-13-502)
	* Linear  [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [Ber14](https://iopscience.iop.org/article/10.1088/1751-8113/47/10/105301) [Ber+17](https://link.springer.com/article/10.1007/s00220-017-3002-y) [CL20](https://link.springer.com/article/10.1007/s00220-020-03699-z) [FLT22](https://arxiv.org/abs/2208.06941) [JLY22a](https://arxiv.org/abs/2212.13969) [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLY22b](https://arxiv.org/abs/2212.14703) [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Exp-darkgreen)]() [Zan+21](https://www.sciencedirect.com/science/article/pii/S2095927321004631)
		* Second-order  [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Exp-darkgreen)]() [SS19](https://doi.org/10.1103/PhysRevA.99.052355)
			* Quantum harmonic oscillator [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Ric+22](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.106.052431)
	* Nonlinear [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [KPE21](https://link.aps.org/doi/10.1103/PhysRevA.103.052416) [Shi+21](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.103.062608) [![download](https://img.shields.io/badge/-FTol-red)]() [LO08](https://arxiv.org/abs/0812.4423) [DS21](https://arxiv.org/abs/2105.07317)  [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLY22b](https://arxiv.org/abs/2212.14703) [Liu+20](https://arxiv.org/abs/2011.03185) [SGS22](https://arxiv.org/abs/2212.10775) [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Zan+21](https://www.sciencedirect.com/science/article/pii/S2095927321004631)
		* Laguerre  [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [CS22](https://arxiv.org/abs/2204.03657)
	
* Partial differential equations [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [CLO21](https://doi.org/10.22331/q-2021-11-10-574) [![download](https://img.shields.io/badge/-QIns-grey)]() [Gar21](https://quantum-journal.org/papers/q-2021-04-15-431/)
	* Linear [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [OMa+22](https://arxiv.org/abs/2205.00645), [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [JLY22a](https://arxiv.org/abs/2212.13969) [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLY22b](https://arxiv.org/abs/2212.14703) [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [CS22](https://arxiv.org/abs/2204.03657)
		
		* Non-homogeneous [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Exp-darkgreen)]() [Bra+20](https://arxiv.org/abs/1909.05820) [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [Arr+19](https://doi.org/10.1103/PhysRevA.100.032306) [Ric+22](https://doi.org/10.1103/PhysRevA.106.052431) 
			* Vlasov [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [ESP19](https://doi.org/10.1103/PhysRevA.100.062315)
			* Poisson  [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [Bra+20](https://arxiv.org/abs/1909.05820) [Sat+21](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.104.052409) [AK22](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.104.052409) [Sah+22](https://arxiv.org/abs/2210.16668) [Lub+20](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.101.010301) [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [Cao+13](https://doi.org/10.1088/1367-2630/15/1/013021) [![download](https://img.shields.io/badge/-Num-darkblue)]() [Arr+19](https://doi.org/10.1103/PhysRevA.100.032306) [Ric+22](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.106.052431) [Liu+21](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.104.022418) [Wan+20](https://link.springer.com/article/10.1007/s11128-020-02669-7)
		* Semi-classical Schrödinger [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLL22](https://quantum-journal.org/papers/q-2022-06-17-739/)
		* Time-dependent Schrödinger [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [Jou22](https://arxiv.org/abs/2205.02358) [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLL22](https://quantum-journal.org/papers/q-2022-06-17-739/)
		
	* Stochastic PDE  [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Kub+21](https://link.aps.org/doi/10.1103/PhysRevA.103.052425) [Alg+22](https://quantum-journal.org/papers/q-2022-06-07-730/)
		* Fokker-Planck [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLY22b](https://arxiv.org/abs/2212.14703) [![download](https://img.shields.io/badge/-QIns-grey)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Gar21](https://arxiv.org/abs/1909.06619)
		* Linear Boltzmann [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLY22b](https://arxiv.org/abs/2212.14703)
		
	* Hyperbolic/Wave-related [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [JLY22d](https://linkinghub.elsevier.com/retrieve/pii/S0021999122007045) [JL22](https://arxiv.org/abs/2202.07834)
		* Wave [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [CJO19](https://doi.org/10.1103/PhysRevA.99.012323) [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [CS22](https://arxiv.org/abs/2204.03657)
		* Maxwell’s [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [CJO19](https://doi.org/10.1103/PhysRevA.99.012323) [![download](https://img.shields.io/badge/-Num-darkblue)]() [NSD21](https://arxiv.org/abs/2112.06086) [NDS22](https://arxiv.org/abs/2212.09113)
		* Klein-Gordon [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [CJO19](https://doi.org/10.1103/PhysRevA.99.012323)
		* Helmholtz [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]()  [![download](https://img.shields.io/badge/-Num-darkblue)]() [Ewe+22](https://ieeexplore.ieee.org/document/9729563/)
		
	* Parabolic [![download](https://img.shields.io/badge/-QIns-grey)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Pat+22](https://arxiv.org/abs/2208.02235)
		* Heat  [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]()  [LEK22](https://arxiv.org/abs/2204.02912) [Alb+22](https://arxiv.org/abs/2208.05805) [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [LMS22](https://link.springer.com/article/10.1007/s00220-022-04442-6) [JLY22a](https://arxiv.org/abs/2212.13969) [JLY22d](https://linkinghub.elsevier.com/retrieve/pii/S0021999122007045) [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLY22b](https://arxiv.org/abs/2212.14703)
		* Black-Scholes [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [FJO21](https://epubs.siam.org/doi/10.1137/21M1397878) [MK22](https://ieeexplore.ieee.org/document/9618807/) [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLY22b](https://arxiv.org/abs/2212.14703)
		* Convection [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLY22b](https://arxiv.org/abs/2212.14703)
		* Hamilton-Jacobi-Bellman [![download](https://img.shields.io/badge/-QIns-grey)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Pat+22](https://arxiv.org/abs/2208.02235)
			
	* Nonlinear [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [JL22](https://arxiv.org/abs/2202.07834)
		* Vlasov-Poisson [![download](https://img.shields.io/badge/-QIns-grey)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [YL22](https://arxiv.org/abs/2205.11990)
		* Schrödinger-Poisson [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [MS21](dx.doi.org/10.3847/1538-4357/abe6ac)
		* Nonlinear-Schrödinger [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Exp-darkgreen)]() [Lub+20](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.101.010301)
		* Burger’s [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Oz+21](https://link.springer.com/article/10.1007/s11128-021-03391-8)
		* Evolution equation  [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [LEK22](https://arxiv.org/abs/2204.02912)

			*Partial Differential Equations with time-domain*
		* Reaction-diffusion [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [LEK22](https://arxiv.org/abs/2204.02912)  [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Exp-darkgreen.svg)]() [Dem+22](https://arxiv.org/abs/2208.11780), [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [An+22](https://arxiv.org/abs/2205.01141)
		* Navier-Stokes [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Gai20](https://www.nature.com/articles/s41534-020-00291-0)
			* Incompressible [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [LEK22](https://arxiv.org/abs/2204.02912) [![download](https://img.shields.io/badge/-QIns-grey)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Lap22](https://arxiv.org/abs/2206.00419)

		* Hamilton-Jacobi [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [JLY22c](https://arxiv.org/abs/2209.08478) [JL22](https://arxiv.org/abs/2202.07834)
		* Black-Scholes-Barenblatt [![download](https://img.shields.io/badge/-QIns-grey)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Pat+22](https://arxiv.org/abs/2208.02235)
	
			*The Black-Scholes-Barenblatt equation is a nonlinear extension to the Black-Scholes equation, which models uncertain volatility and interest rates derived from the Black-Scholes equation.*

* Koopman–von Neumann formulation [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [Jos20](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.2.043102) [JLY22c](https://arxiv.org/abs/2209.08478)

* Nonlinear Schrödinger equation formulation [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [Llo+20](https://arxiv.org/abs/2011.06571)

*  Linear embedding of nonlinear dynamical systems [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [ESP21](https://aip.scitation.org/doi/10.1063/5.0040313) [JLY22c](https://arxiv.org/abs/2209.08478) [![download](https://img.shields.io/badge/-Num-darkblue)]() [Liu+20](https://arxiv.org/abs/2011.03185)
	
* Finite element method [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [MP16](https://doi.org/10.1103/PhysRevA.93.032324)
	
* Quantum Simulation [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [BCK15](https://ieeexplore.ieee.org/document/7354428/)
	* Sparse Hamiltonians [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [Ber+07](https://link.springer.com/article/10.1007/s00220-006-0150-x) [Ber+14](https://doi.org/10.1088/1751-8113/47/10/105301)
	* Imaginary time evolution [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [McA+19](https://www.nature.com/articles/s41534-019-0187-2)
	
* Lattice Boltzmann algorithms [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Bud21](https://arxiv.org/abs/2103.03804)

* Quantum lattice algorithms [![download](https://img.shields.io/badge/-QIns-grey)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [And+22](https://arxiv.org/abs/2211.16661) [Kou+22](https://arxiv.org/abs/2209.08523) [Oga+18](https://arxiv.org/abs/2209.08523); [Ram+21](https://aip.scitation.org/doi/10.1063/5.0067204) [Vah+20a](https://doi.org/10.1080/10420150.2020.1845685) [Vah+20b](https://arxiv.org/abs/2010.12264) [Vah+21a](https://arxiv.org/abs/2010.12264) [Vah+21b](https://www.tandfonline.com/doi/full/10.1080/10420150.2021.1891059) [Vah+22](https://www.tandfonline.com/doi/full/10.1080/10420150.2022.2049784) [VSV20](https://www.tandfonline.com/doi/full/10.1080/10420150.2020.1718136) [VVS20](https://www.tandfonline.com/doi/full/10.1080/10420150.2020.1718135) [Vah+21c](https://doi.org/10.2139/ssrn.3996913) [Vah+20c](https://doi.org/10.1017/S0022377820001166) [Vah+19](https://doi.org/10.1016/j.cnsns.2019.03.016) [Vah+20d](https://doi.org/10.1017/S0022377820001166) [Yep02](https://arxiv.org/abs/quant-ph/0210093) [Yep05](https://link.springer.com/article/10.1007/s11128-005-0009-7) [Yep16](https://doi.org/10.1117/12.2246702) [VYV03](https://linkinghub.elsevier.com/retrieve/pii/S0375960103003347) [Vah+11](https://doi.org/10.1145/2063384.2063416) [Vah+10](https://doi.org/10.1109/HPCMP-UGC.2010.15) [Oga+16a](https://doi.org/10.1080/10420150.2015.1137916) [Oga+16b](https://doi.org/10.1080/10420150.2015.1137916) [Oga+15](https://www.tandfonline.com/doi/full/10.1080/10420150.2014.988625) [Shi+18](https://link.aps.org/doi/10.1103/PhysRevE.97.053206) [And+23](https://arxiv.org/abs/2211.16661)

	*Highly parallelizable approach amenable to classical supercomputers, allowing the study of (Klein-Gordon-)Maxwell’s equations, the Gross-Pitaevski equation, the nonlinear Schrödinger equation, and the KdV equation. In some cases, the method may also be suitable for fault-tolerant quantum computers*
