# Ship_Performance
This is a project to predict the performance of fuel comsumption versus speed for ships

# Backgroud
One of the fundamental problems in maritime transportation is predicting how much fuel will be
used on an upcoming voyage. Imagine telling the vessel to go a certain speed, and you need to
know how much fuel will be consumed across the various environmental conditions along the
voyage. To begin to tackle this problem, we first need a performance model of the ship. Such a
model will output a prediction of the rate of fuel usage given a set of features.

The speed of the ship (measured in knots) is the biggest predictor of the rate of main engine
fuel consumption (measured in metric tonnes per day). In addition, other operating and
environmental factors also influence main engine fuel usage: how loaded the ship is (measured
via draft [ https://en.wikipedia.org/wiki/Draft_(hull) ]), wind speed and direction,
acceleration/deceleration, rudder angle, time since last maintenance, sea state, current, and
others. There are also other features like engine power, shaft RPM, and GPS distance, which
may be useful. But think carefully about these features and how they relate to the problem of
speed+env predicts fuel. For example, engine power is better thought of as an output of this
model than an input.
