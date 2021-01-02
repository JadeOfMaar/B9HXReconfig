# B9 HX Reconfig
### Licensed: CC-BY-NC-SA
Rebalances B9 HX for contemporary KSP gameplay standards.

![Engine modes](https://i.imgur.com/VXOOvg8.png)
![NSWR](https://i.imgur.com/8A1pYs0.jpg)

HX Reconfig brings B9 HX forward in gameplay balance according to its role: to provide immense cuboid parts for building interplanetary megaships. The problem here is that stat-wise, these parts have been left in the past and the default settings for its one heavy engine are very poor for making viable long-range ships.

B9 HX Reconfig performs/provides the following:
* Makes all parts less fragile on impact and more tolerant to aero heat (by very modest amounts).
* Makes the one fission reactor a weaker RTG but also compatible with Near Future Electrical and Wild Blue Industries: DSEV.
  * By default it has a ~100 EC/s RTG, and demands 1MW of cooling while producing 6000 EC/s.
  * With NF Electrical it will demand 6MW of cooling.
  * In Classic Stock mode with WBI DSEV, it's a fusion reactor, producing 12000 EC/s but requiring an investment of 8000 EC to start.
* Clones the RCS blocks and enables switchable RCS fuel feature:
  * Mono (CRP): MonoPropellant; IntakeAtm; ArcJet (LH2 + EC);
  * Mono (WBI): MonoPropellant; CompressedAtmosphere; Nitronite; ArcJet (Propellium + EC)
  * Bi (CRP): LFO; LH2O; 
  * Bi (WBI): LFO; PropLox;
* Clones the heavy engine. Now there are three of it:
  * The original engine is a proper hybrid plasma LFO and super plasma nuclear rocket.
  * One clone will use Nuclear SaltWater, Karborundum or Explodium and behave as a nuclear saltwater rocket, providing unreal TWR and decent Isp at the cost of the entire ecosystem of any world it is used on.
  * One clone will use CRP Liquid Hydrogen (or WBI Propellium) and serve as an Epstein-alike fusion drive with secondary afterburning mode.
* Integrates with WBI Play Mode switcher to change from using B9 Part Switch for resource switching and use Classic Stock equivalent of propellants, WBI OmniStorage for tanking and preserve B9 mesh switching separately.
* Provides unique and all-new plumes for each engine mode and for RCS modes where necessary.
