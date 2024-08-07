Importing pywhatkit Library:

    import pywhatkit as pwt: This imports the pywhatkit library, which is used for automating WhatsApp messages.

Defining Contacts:

    contacts = []: This list stores the phone numbers to which messages will be sent.
    Logging:
        logging.basicConfig: Sets up logging to a file named whatsapp_messages.log with the specified format.

    Function Definition:
        send_messages(contacts, message): Defines a function to send messages to a list of contacts.

    Try-Except Block:
        Adds error handling to catch and log any exceptions that occur during message sending.

    Dynamic Full Number:
        Constructs the full number with country code dynamically.

    Main Block:
        Uses the __name__ == "__main__" block to allow the script to be imported without running the message sending function.