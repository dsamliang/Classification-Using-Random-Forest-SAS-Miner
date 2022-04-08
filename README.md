# Classification-Using-Random-Forest-SAS-Miner

**Dataset:**
-
- ![image](https://user-images.githubusercontent.com/98597962/162492399-39a8ddb2-2447-4fd4-bdb4-4b832ed88be2.png)


**Steps:**
-
1. Add a data source
2. Set 'good_bad' role as target:
  - ![image](https://user-images.githubusercontent.com/98597962/162492479-bdb3cd47-73a6-4a90-a322-a8f45543c046.png)
3. Create a new Diagram
4. Drag the data source to the diagram 
5. Drag HP forest node from HPDM
- ![image](https://user-images.githubusercontent.com/98597962/162492825-abe63fc0-9833-4f3f-803b-fe7a9e2afeb8.png) 
6. Run the node
- ![image](https://user-images.githubusercontent.com/98597962/162493066-0175543b-4cd6-4dd8-b307-caeedeac6122.png)
- We can see that the misclassification rate plots begin to flatten after containing more than 20 tress, which means adding more tress does not have a significant effect on the misclassification rate of the model. 
7. Update maximum number of trees value to 20 in this case after analyzing misclassification rate
- ![image](https://user-images.githubusercontent.com/98597962/162493444-ade2a583-52b1-443d-a07c-54c6a3a99024.png)
8. Import data partition node from sample
- ![image](https://user-images.githubusercontent.com/98597962/162493731-44966f04-0bad-4ffa-9708-80fdcaf03d6b.png)
- ![image](https://user-images.githubusercontent.com/98597962/162493766-daea1c6a-d398-429d-b189-aac7de04bded.png)
9. Run HP forest node and Visualize results

**Results:**
- 
-  ![image](https://user-images.githubusercontent.com/98597962/162494724-1bfd5273-ffb9-4678-ae40-be8b43a98724.png)

