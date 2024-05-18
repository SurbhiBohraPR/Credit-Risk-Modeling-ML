# Credit-Risk-Modeling-ML

Input Features - Cibil Data / Internal Dataset - 85
Output Features - Credit card give or not - 1 Target Features 
Priority Levels - P1 - Best 
                  p2 - Second Best 
                  p3 - third best 
                  p4 - Not Good


 EDA - if df2 - if -99999 >10,000 column drop , else row drop
 Label Encoding - Only in Ordinal Feature ( ex : school, colledge , graduation etc )
                  ( Married / single ) we use Chi-square in this it provie contiengacy table (make combination table with all varible)


 Hypothesis testing
 Infencial stats

# Are These associated ( Maritial status andapproved flag)
  1. H0: They are not associated (Opposite of what we have to prove)
  (Null Hypothesis / Because it is true )

  2. H1: They are associated (What we have to prove write here)
  (alternative Hypothesis)

  3. Calculate Alpha (5%) - margin of error
       Significance level
       strictness level (Assume:0.05)
       less risky project - alpha >5%
       more risky project - alpha < 5%

  4. Confidence Interval
       (1-alpha) 
       
  5. Calculate evidance against H0 
   p-value(how much evidance against null value) > Accept Hypothesis 
   p-value < reject H0 Hypothesis
   P-value is calculate by followng test(Most frequntly used )
   Chi square(chi square table)
   T-test (t-test)
   Anova (fdistribution table)
    +
   Degree of Freedom 
   = we get table (pvalue)
 6. we comapre aplha with pvalue
      if pvalue  <= aplha
            Reject h0
      if pvaue > aplha
            why we don't we write (accept the null hypothesis)(we don't have proper evidance)
            fail to reject the null h0



 Chi square test Cat vs Cat ( Catagorical vs catagorical)
 T-Test ( Cal vs Numerical)      2 catagories
 Anova (cat vs Numerical)   >= 3 Catagories



 # Multicollinearity for all the numerical features ( to see if there is any relation between all the columns or not) (VIF)
  Removing mticollinarity is important ( we calculate VIF value for each column)
              Variance Inflation Factor
              Used to identify multicollinearity among IVs
              Takes R-squared value for each IV and eliminate if crosses a threshold 

              


  Multicollinearity vs correlation 
  Multicollinearity = predictibility
  correlation = +ve or -ve
  we mostly use multicollinerity 

  correlation is ony for the linear correlation between the columns 
  In convex function , correlation gives you misleading values  
  
  
  
 





  
