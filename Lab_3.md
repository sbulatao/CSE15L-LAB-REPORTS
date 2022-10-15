# WEEK 3 LAB REPORT
## Part 1
   This picture shows the code for a **Simple Search Engine**:
![Search Engine Code](https://user-images.githubusercontent.com/114209345/195958662-2f1a4468-a896-4036-96eb-1794cafc24b1.png)
    
   Once when you ctrl+click the link after it is complied and run we see this image:
   ![local search engine](https://user-images.githubusercontent.com/114209345/195959811-5e813c33-75cd-4a22-a520-3fccd1f2ea0b.png)

### Add Path
   Within the add path portion of the code, we need to do the following:
   
     - split the url query at "="
     - check if parameters[0] is equal to "s"
     - a count that inceases everytime we add a new string
     - update the String str with a space " "
     - see what is being added to the string parameters[1]
     - see the result of the string str
    
   We see what string is being added and the overall string that have been added prior from last added strings.
   
   Once that is finished we would see this result:
   ![complete add](https://user-images.githubusercontent.com/114209345/195959678-3b6f0991-081a-482a-866a-3d1582e8193e.png)

### Search Path 
  Within the search path porrtion of the code, we need to do the following:
  
    - split the url query at "="
    - create a new String called result
    - create a holder array to hold the strings that contain characters that we are trying to find
    - update result from holder with spaces included
    
   We could simplify the code but for now, this would do since it works. Here are some examples when we are searching specific characters:
       
    Here we are searching words containing "app":
   ![search app](https://user-images.githubusercontent.com/114209345/195960491-558c6793-c909-40d0-8a82-f3460bb0444b.png)

    Here we are searching words containing "g":
   ![search g](https://user-images.githubusercontent.com/114209345/195960566-e19f311e-05b2-4bda-b4ab-82933a714dbb.png)
   
    Here we are searching words containg "t":
   ![search t](https://user-images.githubusercontent.com/114209345/195960598-b68bda64-4379-4d32-8ebb-461af968bbf8.png)
   
    Here we are searching words containing "tr":
   ![search tr](https://user-images.githubusercontent.com/114209345/195960629-187dffec-1ee8-4835-9427-13100f311af0.png)
   
---------
## Part 2
### Array Methods
      Before code is fixed:
   ![not fixed code](https://user-images.githubusercontent.com/114209345/195961789-5f988c70-7f70-4338-9363-da9fe744f22d.png)

      First attempt to fix:
   ![first attempt](https://user-images.githubusercontent.com/114209345/195961930-ae3c1f6e-8837-40a4-b785-6ad00823ff49.png)
   ![the output](https://user-images.githubusercontent.com/114209345/195961972-9830f1b0-253d-45ab-9180-44dce1c88e3e.png)

      After code is fixed:
   ![final image](https://user-images.githubusercontent.com/114209345/195961565-85921100-f1fd-4f4d-b592-24fb7aef1cc6.png)

      The test:
   ![test](https://user-images.githubusercontent.com/114209345/195961875-9b9cb190-14e7-4942-9773-2cde74a355fb.png)


#### The failure-inducing input (the code of the test)
The code of the test would give me [7, 7, 6, 5, 5, 6, 7, 7] rather than what is expected [7, 7, 6, 5, 4, 3, 2, 1]
#### The symptom (the failing test output)

#### The bug (the code fix needed)

#### Then, explain the connection between the symptom and the bug. Why does the bug cause that particular symptom for that particular input?


### List Methods
       Before code is fixed:
   ![not fixed code](https://user-images.githubusercontent.com/114209345/195966265-201b9e04-321a-4921-872d-0d14c4c509a4.png)
       
       First attempt to fix:
   ![filter](https://user-images.githubusercontent.com/114209345/195966443-2ad92e78-fed8-4f2a-b0b7-e21bb0e33897.png)
   ![filter test](https://user-images.githubusercontent.com/114209345/195966475-28ee8c1c-1656-4660-8963-29b5dc8ca56a.png)
   ![merge](https://user-images.githubusercontent.com/114209345/195966568-e1e730aa-963d-4db0-96e1-e6c2f07af481.png)
   ![merge test](https://user-images.githubusercontent.com/114209345/195966555-06dab484-67b2-4006-9d4a-32e195e16ca0.png)
   
       After code is somewhat fixed:
   ![final filter](https://user-images.githubusercontent.com/114209345/195966640-9e3abdef-9d3d-4999-a22c-73fa03cd1a13.png)
   ![final merge](https://user-images.githubusercontent.com/114209345/195966647-4cad500c-7d24-4488-8a6c-2f814e45c79f.png)
       
       The test is sadly not finished:
   ![filter tests](https://user-images.githubusercontent.com/114209345/195966348-f7aaf7ee-d304-4f0a-88ea-2efee13da9ac.png)
   ![merge tests](https://user-images.githubusercontent.com/114209345/195966744-2b488860-771b-4434-afe7-6bcc4b6a70c6.png)
       
#### The failure-inducing input (the code of the test)

#### The symptom (the failing test output)

#### The bug (the code fix needed)

#### Then, explain the connection between the symptom and the bug. Why does the bug cause that particular symptom for that particular input?
