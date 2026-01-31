
<img width="808" height="252" alt="image" src="https://github.com/user-attachments/assets/d7e3f7c5-71a9-46b4-b769-ee6f7fdc08ab" />

# Click The Below Link To Navigate To The Above Playlist: 
[Direct Link Of The Above Playlist](https://youtube.com/playlist?list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8&si=y38Ep_Aoro5qK9kq)

# Instructor Name: `Bogdan Pshonyak`
#### [LinkedIn](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://www.linkedin.com/in/bpshonyak&ved=2ahUKEwilx6vqr7aSAxVMoK8BHWQFFH4QFnoECCQQAQ&usg=AOvVaw3N6FTrRJP9TFahBz2tu2Ta)
#### [Github](https://github.com/letsgetrusty)






# `Structs In Rust Lecture`: 
#### In This Video The Content Is About: Chapter-5 Of Rust Book And i.e., `Grouping Related Data Using Structs`. 
#### Explore Why People Will Say That: `Enums` And `Structs` Are Building Blocks For Creating New Types In Rust? What Does It Mean?  
#### Explore What Is The Difference Between The Methods And Functions In The Context Of Rust?
#### Does Rust Is OOP Based? 
#### How To Define Methods And Associated Functions On Structs? 





# Structs: 
- It Is A Programming Construct Which Allows To Group Related Data Together.
  - Struct Allows To Group The Related Data Together (Think Of It Is Like Grouping The Object Attributes In A Class In OOP Context).
- It Allows Us To Create A Custom Data Type.
- We Will Be Using The Keyword `struct` To Create The Structs In The Program.
- Like Tuple, Structs Also Allows To Group The Data Of Different Types.
  - But By Grouping The Data In Structs We Will Get The Benifits Such As:
    - Creating A New Type By Defining The Structure By Name.
    - Allows Us To Gives The Names To The Data Inside The Struct And This Allows To Refer Our Data With Name Instead Of Indexes.
    - Etc. (Explore About Them And List Here) - Pending.
   
#### Standard Syntax: 
```rs
struct StructName{
    // Fields. 
}
```
- Note: Structs In Rust `Camel Case Naming Convention`.
  - What Does It Mean By Camal Case:
    - Each Word Starts With The Capital Letter.
    - No Spaces Or Any Other Symbols.
  - E.g.,
    - StudentInformation.
    - ExaminationDepartment.
    - ComputerScienceEngineering.

- What Are Things Inside A `Struct` Called?
  - In Rust, The Variables Inside A Struct Are Called Fields,Not `Attributes` And Not `Members`.
    - Refering Them As `Attributes` Is Wrong.
    - Refering Them As `Members` Is Not `Idiomatic Rust`.
    - Correct Terminology Is: `Struct Fields`.

#### Example: 
```rs
struct User{
    name: String,
    email: String, 
    sign_in_count: u64,
    is_active: bool, 
}

```


# `Note:` Understanding Tuples And Structs Side By Side: 
#### Both Structs And Tuples Can Group The Data.
#### Both Structs And Tuples Can Group The Differebt Types Of Data. 
  - Tuples Can Contain Different Types Of Data (Different Type Of Tuple Elements).
  - And Similarly Structs Can Contain Different Types Of Data (Different Type Of Struct Fields).
#### The Real Difference Between The Structs And Tuples Is About `Semantics, Readability, Safety, And Behavior`.
#### Tuples Are Used For Convenience. Structs Are For Clarity And Design. 
  - If The Data Means Something, Make It A Struct. If It's Just Passing Things Around, Use A Tuple.






# 2 Minutes Completed!

