# Warehouse_Centralization_Data_Analysis
Evaluation of Client Service Level (CSL) to perform warehouse centralization 


The company operates in three Baltic countries: Estonia (EE), Latvia (LV) and Lithuania (LT).
Currently, each country has a local warehouse (EED1, LVD1, LTD1), which receives goods from
suppliers and serves only local customers (Figure 1). It is decided that the centralization of
goods flows will be carried out, which means that the goods from the suppliers first arrive at
the central warehouse (LVD1) located in Latvia, and only then they will be delivered to Estonia
(EED1) and Lithuania (LTD1) (Figure 2). The centralization process is gradual, and the flow of
different brands of goods is gradually switched to a central warehouse.

<img width="482" alt="image" src="https://github.com/ManderB/Warehouse_Centralization_Data_Analysis/assets/123018756/841e44d1-3531-44e3-a265-d01c44f15335">

Company management needs to evaluate how effective this process is, and one of the
indicators that allows to do it is CSL (Customer Service Level):
𝐶𝑆𝐿 = 𝐷𝑃𝐴𝑑𝑒𝑙𝑖𝑣𝑒𝑟𝑒𝑑/𝐷𝑃𝐴𝑜𝑟𝑑𝑒𝑟𝑒𝑑 ∗ 100,
where DPAdelivered – number of delivered boxes;
DPAordered – number of purchased boxes. 

**The company's information system does not allow to find CSL
automatically, so it will have to be done manually.**

**Task:**

Using historical data from the attached files, find out what changes the CSL had after switching
the flow of goods to the central warehouse for each brand individually as well as all goods
together

<img width="242" alt="image" src="https://github.com/ManderB/Warehouse_Centralization_Data_Analysis/assets/123018756/c3205604-d98e-42e3-9c84-17864a995bc9">

Please evaluate CSL 12 month before and 12 month after the switching date.

**Note:** After switching the flow of goods to the central warehouse LVD1, the customer service
level CSL is calculated only for those customers who receive the goods from LVD1 (EED1 and
LTD1 warehouses also become LVD1 customers).
