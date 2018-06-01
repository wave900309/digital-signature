# digital-signature

#1.generate:
hash = hash(data)
signature = private_key_encrypt(hash)

#2.verify:
if(hash(data) == public_key_decrypt(signature)){
    verified;
} else {
    error;
}
