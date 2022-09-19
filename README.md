# LMS-RLS-DNN

`d` is the desired signal, where \
`y_noise` is the actual signal received.

The length of the signal is $250$ seconds. We will use three methods to filter the noise and compare the performance.
1. LMS filter
2. RLS filter
3. DNN

For detail of these methods, please refer to the slides.

In the jupyter notebook, we will get three prediction errors.
They were obtained from

$10\log_{10}\sum\limits_n (d(n)-\hat{y}(n))^2$

That is, we will compare the prediction errors during $~t=200\sim250$ (sec).
