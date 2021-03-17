# plotting-linear-regression-residuals
Plotting linear regression residuals for both single linear model and null model.

`ggplot(d,aes(x=log.body,y=log.brain))+geom_point()+
       geom_smooth(method = "lm", se = FALSE, color = "blue")+
  geom_segment(aes(xend =log.body, yend = .fitted),color="red")+
  geom_point(aes(y = .fitted), shape = 1)+theme_bw()`


<figure>
  <img src="fitted versus null model residuals.png" alt="Trulli" style="width:100%">
  <figcaption>Fig.1 - Regression segments of fitted brain size values of mammals explained by weight compared to the null model</figcaption>
</figure>

<figure>
  <img src="elephant.gif" alt="Trulli" style="width:5%">
  <figcaption>https://www.popsci.com/what-does-brain-size-have-to-do-with-intelligence/</figcaption>
</figure>
