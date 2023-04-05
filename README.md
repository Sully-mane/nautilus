# nautilus
Nautilus Learning Rate Scheduler
When fine-tuning a pretrained model like LLaMA, it's essential to use a smaller learning rate to prevent the model from deviating too far from the original weights. Starting points for the initial learning rate a and b:

Initial learning rate: Start with a smaller learning rate, like 1e-5 or 5e-5, since fine-tuning a pretrained model. Experiment with values in the range of [1e-6, 1e-4] to find the optimal learning rate for your specific task.
a: A reasonable range to explore for 'a' could be [0.1, 1.0]. You may need to adjust this range depending on the problem and the learning dynamics of the LLaMA model.
b: Start by exploring the range [0.1, 0.5] for 'b'. Depending on the problem and the LLaMA model's learning dynamics, you may need to adjust this range.
To fine-tune the LLaMA model using the Nautilus learning rate scheduler.
