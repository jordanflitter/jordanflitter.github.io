---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: CV/CV-Jordan Flitter.pdf
    design:
      css_class: dark
      # Avatar customization
      avatar:
        size: xl  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: why
    content:
      title: 'Why'
      subtitle: ''
      text: |-
        Ever since I was a kid I wanted to understand **why** things work the way they work
        (it's quite amusing that only recently I started to ponder **why** I have this obsession).
        I was fascinated by the concept that there is a set of fundamental laws and building blocks
        that can explain everything. **That drove my motivation to study particle physics** during my
        BSc and MSc degrees. Specifically, I found high energy physics (HEP) to be most appealing,
        since this is where things get really interesting!
        
        For example, I was amazed to learn that our most profound physical theories, general
        relativity and quantum field theory, are founded on elegant symmetry arguments. Even more so,
        I was deeply impressed to learn that nature appears to work in more mysterious ways than meets
        the eye: that time is relative; that the fate of particles is not deterministic; that particles
        are nothing more than excited states of universal fields that all of us share. While these ideas seem trivial to some
        people (and maybe boring to others), I felt that by understanding them better I get closer to 
        "God", and I'm not even a religious person!
        
        Regardless, that makes you wonder: what other wonders have yet to be discovered? There are, for example,
        massive beasts in outer space that prevent extracting any information from their interior. What are they
        trying to hide there??? 🧐

        It also makes you wonder how complete is our understanding of reality. I mean, if string theory says that
        our world actually has 11 dimensions, then anything is possible, right? It is interesting that we know for
        a fact that our understanding is incomplete. For example, general relativity predicts that the density and
        gravitational fields in black holes approach infinity as we go towards their center, which is a mathematical 
        concept that physicists do not accept as an accurate description of nature.

        Moreover, despite the tremendous success of the standard model (SM) of particle physics, it still cannot answer
        some big questions (here's a nice [list](https://en.wikipedia.org/wiki/List_of_unsolved_problems_in_physics#High-energy/particle_physics) from Wikipedia that summarizes them). Perhaps the biggest one is how the force of gravity 
        should be incorporated in the SM and how it would align with general relativity. This is considered by many as the holy grale of theoretical physics.

    design:
      columns: '1'
  - block: markdown
    id: how
    content:
      title: 'How'
      subtitle: ''
      text: |-
        **How** should we answer these questions and improve our understanding of reality? While accelarators/colliders have been 
        the best way to refine our knowledge of particle physics in the 20th century (up to 2012 with the discovery of the 
        Higgs boson) I believe that this approach has been exhausted and we should not expect to get new exciting discoveries in the 
        foreseenable future (we will see how badly this statement is going to age...). I simply do not believe that we will gain enough
        energy to probe particle physics on sufficient small scales and discover new physics (again, this statement might age badly).
        Instead, I believe that the best approach to study particle physics is to study the Universe as a whole --- **cosmology**.
        
        It is quite interesting that by studying the largest scales of the Universe we could learn more about its smallest scales.
        But it makes sense for two reasons: (1) the Universe was once much smaller and much more energetic, when particle physics had a more crucial role in shaping its state, and (2) any variation in the nature of particle physics on the smallest scale has the potential to leave an imprint on the largest scales, simply because there are more particles on the largest scales! I actually love it that in my work I get to ponder about both the largest and smallest scales of the Universe, while living my life within the human scale (which is a good medium scale: the size of the observable Universe is about $10^{27}$ meters while Planck scale is about $10^{-35}$ meters).

        When one considers the SM of particle physics in the context of cosmology, one finds many challenges to the model, even more 
        severe than the HEP challenges. [This Wikipedia webpage](https://en.wikipedia.org/wiki/List_of_unsolved_problems_in_physics#Cosmology_and_general_relativity) summarizes the challenges in the standard model of cosmology (known as $\Lambda$CDM) but I outline those that have to do with open particle physics problems:
        
        1. **Dark matter.** There is a growing evidence that the gravitational fields in the Universe on its largest scales are dominated by a type of matter that cannot be seen nor be touched as it is speculated to not interact directly with electromagnetic radiation. **Many observations suggest that this invisible matter, named **dark matter** for obvious reasons, is five times more abundant than ordinary matter**, the latter is basically all the stuff that we interact with in our daily lives. This is mindblowing; just imagine that all the particles that assemble the world we see and touch, are completely outnumbered by this mysterious dark matter. And yet, all the particles from the SM have been ruled out as being possible candidates to dark matter. The only thing that we know (or we think we know) about dark matter is that it behaves like matter (in the sense that it interacts graviationaly with itself and with ordinary matter) and that it is dark. That's it!
        2. **Dark energy.** It is remarkable that not only ordinary matter is much less abundant compared to dark matter, but both kinds of matter do not form the main contribution to the energy of our Universe. According to $\Lambda$CDM, roughly 5% of the energy budget of the present Universe is in the form of ordinary matter and 25% in the form of dark matter. **The remaining 70% come from dark energy which causes the expansion of the Universe to be accelarated**. If at least we know that dark matter is a form of matter, we have no idea what is the physical mechanism behind dark energy. In $\Lambda$CDM, dark energy is associated with the energy density of the vacuum. Yet, we know that dark energy cannot fully be described by the energy of the vacuum; comparison between the inferred value from consistent observations of dark energy with the value predicted by quantum field theory suggests that there is a discrepancy between the two values of order $10^{120}$! Understanding better the nature of dark energy is therefore one of the most urgent challenges in modern theortical physics.
        3. **Cosmic inflation**. In order to explain the flatness of the Universe and its homogeneity on its largest scales (as well as the inexistence of magnetic monopoles) it is believed within the $\Lambda$CDM pardigm that the Universe went a phase of inflation prior to the hot Big Bang (the moment in which the SM particles were "created"). **During the inflationary epoch, the Universe expanded in an exponential rate, thereby increasing its size and lowering its temperature by orders of magnitude within a fraction of a second**. While the theory of cosmic inflation succesfully solves the flatness and horizon problems, we do not have a smoking gun proof that cosmic inflation truly happened. Moreover, the exact physical mechanism that generated inflation is still not fully understood, including the "inflaton" fields that drove the inflationary expansion. In the simplest model of inflation, there is only one inflaton field that resulted in adiabatic Gaussian initial conditions for the hot Big Bang. These kinds of initial conditions agree well with observations, but different models of inflation (that predict different initial conditions) have not been ruled out yet. As in the case of dark matter and dark energy, the SM does not provide an explanation to the physics of inflation (even more so, it is inflation and the subsequent epoch of reheating that is believed to determine the SM physics).
        4. **Matter asymmetry**. According to the SM, every particle has its own dual antiparticle which is a flipped version of the particle, with reversed charge and parity (or equivalently, the antiparticle can be thought of as a particle going backwards in time, due to CPT symmetry). Some particles, like the photon, are their own antiparticle. Others, like the electron and the proton, are not their counterpart antiparticles (since they are electrically charged), called positron and anti-proton, respectively. Theoretically, just like protons and electrons are allowed by the SM to form atoms, or matter, anti-proton and positrons are allowed to form antimatter. According to the SM, there is no reason to believe that our Universe will favor more matter particles over antimatter particles, since the two kinds of particles are completely symmetrical in the equations. Yet, observations suggest just that the Universe has much more matter than antimatter; **for every one antimatter particle there are about one billion matter particles!** This matter asymmetry implies that either matter and antimatter were created unequally during the Big Bang, or alternatively that they were created in nearly equal amounts and some process led to this asymmetry later on. While the SM does contain the fundamental ingredients to generate some matter asymmetry, the resulting asymmetry is far too small to be consistent with observations.

        Besides the above challenges, there are other open problems that $\Lambda$CDM is facing, that will may or may not invlove modifications in the SM of particle physics. Below I outline the main one.
        
        A key parameter in $\Lambda$CDM is the present expansion rate of the Universe, known as the Hubble constant. This quantity can be directly measured locally, by measuring the recession velocity of distant galaxies as a function of their distance from us --- the slope of this curve is the Hubble constant. Alternatively, measurements of the anisotropies in the cosmic microwave background (CMB), a radiation that originated not long after the Big-Bang, can give us some clue on the Hubble constant. The best fit to the CMB anisotropies power spectra, under the assumption of $\Lambda$CDM, yields a Hubble constant that is different from the direct measurement by a statistically significant amount. Not only that this discrepancy has been repeating itself in different measurements that have been carried over the last decades, but it has also been growing! **This discrepancy between "late-Universe" and "early-Universe" measurements of the Hubble constant is known as the Hubble tension** (some people may even call it the Hubble crisis). One possible explanation for the Hubble tension is that perhaps our observations (from either late-Universe or early-Universe measurements, or both) suffer from an unknown systematic error that affects the inferred Hubble constant. However, for this explanation to hold, it requires the systematic error to be present in many different instruments that have been used for observations. Another explanation suggests that both measurements of the Hubble constant from late-Universe and early-Universe observations are correct, and the discrepancy between the inferred values is a sign that $\Lambda$CDM has to be modified in order to explain the two different Hubble constants. Some models that go beyond $\Lambda$CDM have been proposed over the years in an attempt to solve the Hubble tension, however none of them has been compelling enough to become the new consensus.

        **While the aforementioned challenges in $\Lambda$CDM are considered as problems in the model, they should be viewed as opportunities** since they provide a window to new physics that otherwise would be inaccessible by any laboratory-based experiment.
    design:
      columns: '1'
  
  - block: markdown
    id: what
    content:
      title: 'What'
      subtitle: ''
      text: |-
        **What** I aim to do in my reasearch is to help the scientific community understand better how to answer the above big questions. I do not necessarily aspire to invent a new theory that would explain the origins of dark matter, dark energy, cosmic inflation or the Hubble tension. Instead, my goals are much more modest. I am more interested in studying how different theories beyond the standard model modify cosmological observables, and how much information we can extract from these theories once they are confronted with data from observations. I try to be as agnostic as possible for each theory I study: I am not looking for confirming/ruling out any particular theory - I am simply looking for the information encoded in theories!
        
        **If you have a cool theory that could be tested with a simulation of any observable - let me know!** I specifically enjoy modifying the differential equations in simulators or their initial conditions, in my opinion that is the best way to study and understand better the physics behind the observable.

        **One of the promosing observables that I am mostly excited about is the 21cm signal**. This signal is sourced from hyperfine transitions in hydrogen atoms that release photons of 21cm wavelength. Once these photons reach Earth their wavelength has been stretched due to the expansion of the Universe, which enables in theory the construction of 3D topological maps of a physical quantity known as the brightness temperature (provided that foregrounds and instrumental noise do not spoil the pure cosmological signal too much). The potential in the 21cm signal is due to our knowledge that the intergalactic medium (IGM) is full of hydrogen: more than 90% of the ordinary matter in the Universe is hydrogen. So there are A LOT of hydrogen atoms that can serve as potential sources of 21cm emission. But more importantly, the 21cm signal can give us information on a huge uncharted region of the Universe, where no other observable can come from. For example, a worldwide effort is being invested by various collaborations to measure the 21cm signal from the **cosmic dawn** --- the epoch in which the first stars and galaxies were formed. As exciting as it sounds, the 21cm signal has even the potential to shed light on the preceding epoch to cosmic dawn --- **the dark ages**. This epoch earned its name because there were no luminous sources at the time and the Universe was practically dark. Still, hydrogen atoms existed during the dark ages, thereby the 21cm signal is the only observable that can teach us something about the physics of the Universe during that epoch.

        **To conclude, the 21cm signal may give us enough information to help answer better the above profound questions.** The signal is very sensitive to the physics of the assumed dark matter, not only because the first galaxies formed inside "halos" of dark matter, but also because any non-gravitational interaction between dark matter and ordinary matter can alter the thermal and ionization history of the IGM, which directly affect the 21cm signal. In addition, any deviations in the initial conditions (due to different inflationary models) would also show its signature on the 21cm signal. And finally, since the 21cm signal is sourced from uncharted regions in our Universe, it could provide a "medium-Universe" measurement of the Hubble constant and therefore improve our understanding for the origin of the Hubble tension. All these reasons motivate me to focus my research on the 21cm signal.
---
