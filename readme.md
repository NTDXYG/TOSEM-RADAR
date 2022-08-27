This package contains three parts, which are RADAR-Attack, RADAR-Defense, and the original dataset.

- **RADAR-Attack**

This directory holds the main code for constructing the adversarial examples, where CodeBLEU is referenced from

[CodeXGLUE/Code-Code/code-to-code-trans/evaluator/CodeBLEU at main · microsoft/CodeXGLUE (github.com)](https://github.com/microsoft/CodeXGLUE/tree/main/Code-Code/code-to-code-trans/evaluator/CodeBLEU)

In addition, we give the code generated by CodeT5 for FD, FDsig and each attack method on Java dataset and Python dataset.

Regarding the fine-tuning scripts for CodeGPT, PLBART and CodeT5, we will release them after the acceptance of the paper.

- **RADAR-Defense**

This directory holds the main codes of information retrieval methods and defense models.

'func_name_gen_data' is the dataset to generate the method name, which is extracted from the original dataset.

'Information Retrieval' is the code for the information retrieval method，'IR_train.py' is a retrieval method for the training set (the retrieval method needs to filter itself)，'IR.py'is a retrieval method for the valid set and test set。'merge.py' is the code that merges the information retrieval results with the original dataset.

'model.py' is the code of our defense model, containing the implementation of UniXcoder and In_trust loss.

Regarding the training code, again we will release it after the paper is accepted.

- **original-dataset**

This directory is where we store our collected data sets and related statistical information.