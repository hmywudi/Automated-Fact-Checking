The impact of climate change on humanity is a significant concern. However, the increase in unverified statements regarding climate science has led to a distortion of public opinion, underscoring the importance of conducting fact-checks on claims related to climate science. Consider the following claim and related evidence:
Claim: The Earth’s climate sensitivity is so low that a doubling of atmospheric CO2 will result in a
surface temperature change on the order of 1°C or less.
Evidence:
1. In his first paper on the matter, he estimated that global temperature would rise by around 5 to
6 °C (9.0 to 10.8 °F) if the quantity of CO 2 was doubled.
2. The 1990 IPCC First Assessment Report estimated that equilibrium climate sensitivity to a doubling of CO 2 lay between 1.5 and 4.5 °C (2.7 and 8.1 °F), with a "best guess in the light of current
knowledge" of 2.5 °C (4.5 °F).
It should not be difficult to see that the claim is not supported by the evidence passages, and assuming the source
of the evidence is reliable, such a claim is misleading. The challenge of the project is to develop an automated
fact-checking system, where given a claim, the goal is to find related evidence passages from a knowledge source,
and classify whether the claim is supported by the evidence.
More concretely, you will be provided a list of claims and a corpus containing a large number evidence passages
(the “knowledge source”), and your system must: (1) search for the most related evidence passages from the
knowledge source given the claim; and (2) classify the status of the claim given the evidence in the following
4 classes: {SUPPORTS, REFUTES, NOT_ENOUGH_INFO, DISPUTED}. To build a successful system, it must be able to
retrieve the correct set of evidence passages and classify the claim correctly.
