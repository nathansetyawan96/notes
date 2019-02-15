# Keras

```python
from keras.layers import Input, Dense

input_tensor = Input(shape=(1,))

# output possibilities: if one class then Dense(1), if two classes then Dense(2)
output_layer = Dense(1)

output_tensor = output_layer(input_tensor)
# output_tensor = Dense(1)(input_tensor)
```

