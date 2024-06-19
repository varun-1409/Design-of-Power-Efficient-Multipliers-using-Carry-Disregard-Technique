# Design-of-Power-Efficient-Multipliers-using-Carry-Disregard-Technique

OVERVIEW                                                                                                                                                       
 Approximate computation is one of the best ways for reducing power consumption and reduces the significant calculation complexities. Approximate circuits have been considered for error-tolenint applications that can tolerate some loss of accuracy with energy efficiency and reduces complexity. design of an approximate N-bit array multipliers based on carry disregarding is proposed aiming at reducing the power consumption and reduces calculation of complexities. The technique involves designing of array multipliers based on carry disregard. Carries can be ignored in various ways, and each method leads to different results regarding the criteria of accuracy and hardware. The necessary simulations will be carried out using ECAD tool like Cadence, Xillinx etc., and the power will be calculated.                              
 EXISTING METHOD                                                                                                                                                       
 The existing method is an 8 bit multiplier with and gates and pi_0 units. At initial stage 8 and gates are used and the outputs of these and gates are given to pi_0 units, which consists of one and gate and one full adder. These pi_0 units are the partial product units. They will generate the partial products. As the circuits connects from one pi_0 unit to another pi_0 unit the carry propagation takes much power and delay is high. So to avoid such factors we have going to propose a design with carry disregarding technique. That is going to reduce the high power consumption.                                                                                           To design an approximate 8-bit multipliers we have used two 8x4 multipliers. These  8x4 multipliers operate in parallel to reduce the critical path delay in the overall 8-bit multiplier and power consumption. This can be  achieved by disregarding carries in the all columns of the 8x4 multipliers. The proposed design disregards carries in the all columns ,allowing each column operate independently  and in parallel. This not only reduces power, delay but also simplifies the partial product units. 
![image](https://github.com/varun-1409/Design-of-Power-Efficient-Multipliers-using-Carry-Disregard-Technique/assets/84139574/514db626-45bf-485b-b830-e1a8ae05aae0)
![image](https://github.com/varun-1409/Design-of-Power-Efficient-Multipliers-using-Carry-Disregard-Technique/assets/84139574/9fa94ef2-ae5b-4ebb-a4b9-8f4c3d2305d3)       ![image](https://github.com/varun-1409/Design-of-Power-Efficient-Multipliers-using-Carry-Disregard-Technique/assets/84139574/d39c69e8-3da7-4518-ab78-7c5c9d1e08a2)      ![image](https://github.com/varun-1409/Design-of-Power-Efficient-Multipliers-using-Carry-Disregard-Technique/assets/84139574/0e7b4b7c-1a24-45b9-86c5-82b1e5d18f7d)
    
 PROPOSED 8*4 CARRY DISREGARD MULTIPLIERS                                                                                                                             
 We have designed some of carry-disregard-based approximate 8x4 multipliers. The total number of proposed 8x4 multipliers are 9, which are cd2 to cda.
 We have designed cd5 ,cd2 & cd9 multipliers. we have disregarded the carries from the second column to specific column. The approximate multiplier cd2 disregards all 
 carries upto column 2, and column 1 to operate in parallel and independently. The approximate multiplier cd5 disregards all carries upto column 5, and column 1 to 6 
 operate in parallel and independently. The approximate multiplier cd9 disregards all carries upto column 9, and column 1 to 10 operate in parallel and independently. 
 The operation of carry disregarding will happen by using the units like pi_1, pi_2,pi_3. In the  cd9 the total number of pi_1 units used are 22 and 2 pi_2 units are 
 used. In the cd5 9 pi_1 units, 2 pi_ 2units and 1 pi_3 along with this 11 pi_0 unit has used. These units will disregards the carry generated in their respective 
 column. This makes the circuits using of less power and also the delay may reduce in the circuit.                                                                       ![image](https://github.com/varun-1409/Design-of-Power-Efficient-Multipliers-using-Carry-Disregard-Technique/assets/84139574/356dd4ad-e0be-41fc-a4e0-d47a58959088)      ![image](https://github.com/varun-1409/Design-of-Power-Efficient-Multipliers-using-Carry-Disregard-Technique/assets/84139574/ff2766e0-1af8-4d29-90bc-96f16dae4756)      ![image](https://github.com/varun-1409/Design-of-Power-Efficient-Multipliers-using-Carry-Disregard-Technique/assets/84139574/6d34d901-9249-4f51-9d2b-9ed3b3ea8e41)     ![image](https://github.com/varun-1409/Design-of-Power-Efficient-Multipliers-using-Carry-Disregard-Technique/assets/84139574/f27226d3-1a4b-4756-bd02-cf7c8a15f5af)       ![image](https://github.com/varun-1409/Design-of-Power-Efficient-Multipliers-using-Carry-Disregard-Technique/assets/84139574/ae6b27af-5194-4b6a-b926-650989617d8a)      ![image](https://github.com/varun-1409/Design-of-Power-Efficient-Multipliers-using-Carry-Disregard-Technique/assets/84139574/1c879b89-ea05-4414-9477-34c08505929e)      ![image](https://github.com/varun-1409/Design-of-Power-Efficient-Multipliers-using-Carry-Disregard-Technique/assets/84139574/e1f89cba-7cdb-406b-9d47-e5802e0c79da)      
 Comparing the power usage of the exact 8_bit multiplier and the proposed 8_bit multiplier circuits                                                                     
 ![image](https://github.com/varun-1409/Design-of-Power-Efficient-Multipliers-using-Carry-Disregard-Technique/assets/84139574/4587a43a-6abe-4970-bee2-9279c54b51c8)  
 The above table shows 	that the power consumption by the exsiting circuit is more as compared to the proposed designs. As the number of design increases the power 
 consumption by the circuit decreases.                                                                                                                        
 CONCLUSION                                                                                                                                                           
 In the proposed work, a new design of approximate Multiplier has employeed by incorporating CDM8S logic circuits which consists of AND gates, Full adders and 
 Half adders. The main idea by incorporating them in the proposed design, which is not only disregarding carry propogation but also reducing power consumption, 
 decreases the complexity. Extensive simulations were conducted and performance indices such as power consumption was  evaluated.The proposed design not only varies 
 for certain CDM8S, for each CDM8 the power consumption will reduce, as the number of CDM8 has increased.This shows the proposed circuit has a better power 
 consumption.     
 FUTURE SCOPE                                                                                                                                                           
 From the results, it is clear that the designed 8-bit multiplier is more power efficient when compared to the exact 8-bit multiplier. Therefore using the partial 
 product units we can design a efficient power multiplier, which are used in many archiceture for the data storing process.


                                                                    









                                                                                                                            
    




