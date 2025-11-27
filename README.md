# Image Classifier — Converted TensorFlow Model

A compact repository containing the exported model files for an image classification project.  
Includes the serialized model, weights shard, and metadata needed to load and run the classifier.


---

## 🔧 Tech Overview

- **TensorFlow.js** compatible model format  
- **JSON model schema** + **binary weight shard**  
- Ready for browser-based or Node.js inference  

---

## ▶️ How to Use

**Load the model in JavaScript:**

```js
import * as tf from '@tensorflow/tfjs';

const model = await tf.loadLayersModel('path/to/model.json');

const prediction = model.predict(inputTensor);
console.log(prediction.dataSync());
```





