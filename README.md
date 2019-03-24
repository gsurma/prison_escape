<h3 align="center">
  <img src="assets/prison_escape_icon_web.png" width="300">
</h3>

# Prison Escape

Python notebooks containing various Prisoner's Dilemma approaches.

# Prisoner's Dilemma

Two members of a criminal gang are arrested and imprisoned. Each prisoner is in solitary confinement with no means of communicating with the other. The prosecutors lack sufficient evidence to convict the pair on the principal charge, but they have enough to convict both on a lesser charge. Simultaneously, the prosecutors offer each prisoner a bargain. Each prisoner is given the opportunity either to betray the other by testifying that the other committed the crime, or to cooperate with the other by remaining silent. The offer is:

* If A and B each betray the other, each of them serves 2 years in prison
* If A betrays B but B remains silent, A will be set free and B will serve 3 years in prison (and vice versa)
* If A and B both remain silent, both of them will only serve 1 year in prison.


	
	                               Prisoner A
	                         --------------------     
	                         |Cooperate| Defect |    
	               |---------|---------|--------|
	               |Cooperate| (1, 1)  | (0, 3) |
	    Prisoner B |---------|---------|--------|
	               | Defect  | (3, 0)  | (2, 2) |
	               ------------------------------
           

## Classic Approach

### Results

<img src="output/classic_tournament_results.png">

---

### Payoffs

<img src="output/classic_tournament_payoffs.png">

## Reinforcement Learning Approach
coming soon!
