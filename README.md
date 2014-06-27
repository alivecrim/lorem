lorem
=====

An extremely useful Lorem Ipsum generator for Java!

### Sample Usage:

##### Words

```java
Lorem.getWords(5, 10);
```
Randomly generates between 5 and 10 words.

```java
Lorem.getParagraphs(2, 4);
```
Randomly generates between 2 and 4 paragraphs.

```java
Lorem.getHtmlParagraphs(2, 4);
```
Randomly generates between 2 and 4 paragraphs wrapped in &lt;p&gt; tags.

```java
Lorem.getTitle(2, 4);
```
Randomly generates a title of 2 to 4 words.


##### Names

```java
Lorem.getName();
```
Generates a random name.

```java
Lorem.getNameFemale();
```
Generates a random female name.

```java
Lorem.getNameMale();
```
Generates a random male name.

```java
Lorem.getFirstName();
```
Generates a random first name.

```java
Lorem.getLastName();
```
Generates a random last name.



##### Phone Numbers

```java
Lorem.getPhone();
```
Generates a phone number in the form: `(800) 555-1212`

### Installation:

You can get the latest release via maven.

```xml
<dependency>
	<groupId>com.thedeanda</groupId>
	<artifactId>lorem</artifactId>
	<version>1.2</version>
</dependency>
```

