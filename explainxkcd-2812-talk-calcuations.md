Used at: https://www.explainxkcd.com/wiki/index.php/2812

OK, when I read about this I was reminded of the section in How To where Randall said (I don't have the book right now so it might now be an exact quote):

> (You'll have to get the power from Phobos to Mars) Which can range from beamed microwave power, to dropping large amounts of rechargeable AA batteries.

Since the power gotten from running a cable from the Sun the Earth is ridiculously low I ran some numbers on transporting power to Earth... via a space elevator carrying rechargeable batteries.

I googled some numbers and turned up with those:

80%~90% for DOD (depth of discharge) of Lithium batteries

0.4 MJ/kg for energy density (Lithium Manganese Oxide battery per [this website](https://www.epectec.com/batteries/chemistry/))

Note: Lithium Cobalt Oxide has a much higher specific energy at >0.72 MJ/kg but has low thermal stability, limited load capabilities and a short life span so we'll ignore it.

Since I can't find any data on the depth of the gravity well from the sun to Earth I'll use escape velocity as a rough approx.

Plugging it into the speed-energy formula gives us:

$$E_{launch}=\dfrac{1}2v_{escape}^2\dfrac{E_{stored}}{0.4MJ/kg}$$

Which [works out to](https://www.wolframalpha.com/input?i=1%2F2*%28617.5km%2Fs%29%5E2%2F%280.4MJ%2Fkg%29) $E_{launch}=4.77 \times 10^5 E_{stored}$ for $v_{escape}=617.5 km/s$. Translating to $E_{launch}= 5.3 \times 10^5 E_{usable}$ for a 90% percent DOD.

That'll give a total efficiency of $\sim 1.89 \times 10^{-6}$, which is *much* better than the power lines but still falls slightly short of the power you can get from just putting the panel on Earth (41.58 bucks a year compared to 58) but could possibly beat it if a more precise required velocity can be found.

Though even if it did beat the Earth sunpanel I'm not overtly optimistic about the payback period.
