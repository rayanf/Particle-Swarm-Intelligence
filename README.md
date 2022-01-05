# Particle-Swarm-Intelligence
Optimizing functions via implementing Particle Swarm Intelligence.

## Usage
Just define your function and call Optimizer with your configuration, and then train it.
```python
solution = Optimizer(function = '#yourfunction', numberOfParticles=1000, w=0.8, c1=0.1, c2=0.1, 
                     ra
ngee=10,optima='max', max_v=5)
solution.train(50)
```
## Example
![Alt Text](https://github.com/rayanf/Particle-Swarm-Intelligence/blob/master/f.gif)



## Contributing
Pull requests are welcome.

## License
[MIT](https://choosealicense.com/licenses/mit/)
