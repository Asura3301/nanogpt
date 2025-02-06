# nanogpt
Personal Projects | Reference for Andrej Karpathy

# Generatively Pretrained Transformer (GPT), following the paper "Attention is All You Need". This is Decoder-only transformer with 10 million parameters for character-level language modeling. Pretrained on Shakespeare dataset. 


---
**Logs After Using Adjusted Hyperparameters**

**Hyperparameters:**
- batch_size = 64 
- block_size = 256 
- max_iters = 5000
- eval_interval = 500
- learning_rate = 6e-4
- eval_iters = 200
- n_embd = 384
- n_head = 6
- n_layer = 6
- dropout = 0.2

---

**Train and Validation Loss:**

10.788929 M parameters
step 0: train loss 4.3170, val loss 4.3208

step 500: train loss 1.8746, val loss 1.9890

step 1000: train loss 1.5243, val loss 1.7047

step 1500: train loss 1.3920, val loss 1.6078

step 2000: train loss 1.3116, val loss 1.5571

step 2500: train loss 1.2533, val loss 1.5324

step 3000: train loss 1.2045, val loss 1.5324

step 3500: train loss 1.1596, val loss 1.5238

step 4000: train loss 1.1249, val loss 1.5429

step 4500: train loss 1.0878, val loss 1.5691

---

**Output of the model:**

And I burrake the temple, which at onceorate

Whip this cause shall answer a single to accomplient;

But, as this sacred power like a love, the fight

That title sovereign months nature is from mine--

Lo, thou unhappy God, Wennestor, and will

Forbid thee end thy kin me death, dost thou king?

And, comest thou think, thou shalt be.


SOMERSET:

'Twas well as body it not so?

GLOUCESTER:

Well, what a writ, what I war?

And there, both am I will keep to thy blood.

3 KING HENRY VI

GLOUCESTER:

Well, what a writ, what I war?

And there, both am I will keep to thy blood.

3 KING HENRY VI


GLOUCESTER:

Well, what a writ, what I war?

And there, both am I will keep to thy blood.

3 KING HENRY VI

GLOUCESTER:

Well, what a writ, what I war?

And there, both am I will keep to thy blood.

3 KING HENRY VI

GLOUCESTER:

Well, what a writ, what I war?

And there, both am I will keep to thy blood.

3 KING HENRY VI


GLOUCESTER:

Well, what a writ, what I war?

And there, both am I will keep to thy blood.

3 KING HENRY VI

GLOUCESTER:

Well, what a writ, what I war?

And there, both am I will keep to thy blood.

3 KING HENRY VI


GLOUCESTER:

Well, what a writ, what I war?

And there, both am I will keep to thy blood.

3 KING HENRY VI

GLOUCESTER:

Well, what a writ, what I war?

And there, both am I will keep to thy blood.

3 KING HENRY VI

GLOUCESTER:

GLOUCESTER:

GLOUCESTER:
Well, what a writ, what I war?

hy blood.

3 KING HENRY VI

KING HENRY VI:

By-horter

---

**Notes:**
- Seems like our model starting to overfitting after 3500 step(valid loss starting increasing)
- Need to more adjust hyperparameters of the model
- Need to improve tokenization technique of the model
