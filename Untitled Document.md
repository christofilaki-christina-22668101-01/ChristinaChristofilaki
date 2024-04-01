|Τερματικός κόμβος|Διεύθυνση IPv4|Μάσκα|
|--|--|--|
|laptop|192.168.0.102|24|
|desktop|192.168.0.103|24|
|homerouter|192.168.0.1|24|
|mobile|192.168.0.100|24|



|Κόμβος Α|Κόμβος Β|Αποτέλεσμα|
|--|--|--|
|homerouter|desktop|ΝΑΙ|
|homerouter|laptop|ΝΑΙ|
|homerouter|mobile|ΝΑΙ|
|laptop|desktop|ΝΑΙ|
|laptop|mobile|ΝΑΙ|
|mobile|desktop|ΟΧΙ|
|mobile|laptop|ΟΧΙ|
|desktop|laptop|ΟΧΙ|
|desktop|mobile|ΝΑΙ|

|Κόμβος Α|Κόμβος Β|Αποτέλεσμα|
|--|--|--|
|desktop/ethernet|homerouter/internet|ΝΑΙ|
