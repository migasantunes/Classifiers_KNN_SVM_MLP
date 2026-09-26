# Classifiers_KNN_SVM_MLP
This project's goal is to construct, train and analyze performances between the following classifiers: K Nearest Neighbors;  Support Vector Machines; Multi-Layer Perceptron

### What was AI used for
- Planning 
- Best values to start with for the parameters
- Helping with understanding some concepts
- Classifier Code jumpstart (just a simple code snippet)
- Code quality review that resulted in changes with the AI's feedback
- **Everything else was done entirely by me, including code, with the use of *sklearn* documentation and researche**

>### Questions to ask to teacher:
>- **Timing measurements:** Do I need to be precise in the measurements for the prediction times of the each models? 
>```python
>    times = []
>    for _ in range(5):
>       t0 = time.perf_counter()
>       y_pred = grid.predict(X_te)
>       times.append(time.perf_counter() - t0)
>    pred_time = min(times)
> ```