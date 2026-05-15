# AI Solution Design for Agriculture Domain

## Task 1: Business Domain Selection

**Selected Domain:** Agriculture

**Reason for choosing Agriculture:**
I chose the Agriculture domain because it plays a vital role in India's economy and employs a large portion of the population. Farmers often suffer heavy losses due to crop diseases that are detected too late. An AI-based solution can help in early detection of plant diseases, reduce crop loss, and improve overall productivity and farmer income.



## Task 2: Define the Business Problem

### What problem is being solved?
The major problem is timely and accurate detection of crop diseases. Diseases in plants spread rapidly, and if not detected early, they cause massive crop loss and financial damage to farmers.

### Who are the users or stakeholders?
- **Primary Users**: Small and marginal farmers (who form the majority in India)
- **Other Stakeholders**: Agricultural extension officers, Farmer Producer Organizations (FPOs), NGOs, and government agriculture departments

### What is the current manual or traditional process?
Farmers usually rely on their own experience or consult local agricultural experts/veterinarians. They observe the leaves and decide whether to spray pesticides or not.

### What are the limitations of the current process?
- Delayed disease identification leading to heavy losses
- Lack of expert availability in rural and remote areas
- High possibility of wrong diagnosis
- Overuse or misuse of chemical pesticides due to uncertainty
- Difficulty in monitoring large areas of farmland manually

**Additional Challenge:**
Most small farmers have low literacy levels and limited smartphone experience. Therefore, any AI solution must be extremely simple, preferably voice-based or with minimal text, and should work in local languages (Hindi/regional languages) to be truly usable.



## Task 3: Identify the AI Task Type

**Selected AI Task Type:** Image Classification

**Explanation:**

This problem is best suited for **Image Classification** because:

- We are given images of plant leaves.
- The goal is to classify each image into a specific category (e.g., Healthy, Early Blight, Late Blight, Rust, Powdery Mildew, etc.).
- Image Classification is the most suitable AI task when we need to assign a single label to an entire image.

This task can be effectively solved using a **Convolutional Neural Network (CNN)**, which is excellent at learning visual patterns from images such as spots, discoloration, lesions, and texture changes on leaves.
