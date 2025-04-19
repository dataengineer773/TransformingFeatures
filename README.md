We want to make a custom transformation to one or more features, In scikit-learn, use FunctionTransformer to apply a function to a set of features We can create the same transformation in pandas using apply
It is common to want to make some custom transformations to one or more features. For example, we
might want to create a feature that is the natural log of the values of the different feature. We can do this
by creating a function and then mapping it to features using either scikit-learn’s FunctionTransformer
or pandas’ apply. In the solution we created a very simple function, add_ten, which added 10 to each
input, but there is no reason we could not define a much more complex function
