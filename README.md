# FaceRecogWithLivenessDetection
There are various ways for verification of identity like ID cards, RFID cards, fingerprint scan, etc. One very
popular mode of verification which is used extensively in smart phones is Face Recognition. However the
implementation of face recognition in most lower end devices is a simple pattern matching or landmark
detection. This can easily be spoofed using the image of the authorized person as the image will have the same
landmarks and thus pass the verification test. This can be very dangerous for companies, banks, museums, etc
which contain sensitive information, money/assets, or high-value items like antiques, paintings, jewels, etc
respectively. If these institutions were to implement the aforementioned simple implementation of face
recognition for security purposes it would lead to major repercussions and very weak security.

Suppose a product based company is working on a project that could revolutionize a particular field and make it
a monopoly in that field. However its competitors may hire someone to disguise as a company personnel and
use the image of the person, which can be easily obtained, to gain entry into the company. Now the impostor
can look through the plans for the idea and if the prototype is ready he can copy the files for it and walk away if
he is able to keep a low profile while in the company. This will completely jeopardize the ambition and mission
of the company.

In this model, for authentication, the person's face is captured by camera which is then processed by the Liveness model.
The liveness model checks if the image input into the camera is that of an actual person or an image/printout (spoof of 
usually an authorized person to gain unwanted and unwarranted entry). On making sure that it is an actual person the 
face recognition model fires up to check whether the person trying to gain entry is an authorized person or not (compares the
face encodings received from the input camera with the ones available in database). Finally the person will be given access or 
denied based on the recognition model's judgement.
