<li id="liModal">
                    <label for="toggleModal" class="buttonOrange">Contactez-moi</label>
                    <input type="checkbox" name="modal" id="toggleModal">
                    <div id="shadowModal">
                        <label id="closeModal" for="toggleModal">X</label>
                        <div class="modal">
                            <h2>Me contacter</h2>
                            <form action="#">
                                <label for="userName">Votre nom:</label>
                                <input type="text" name="userName" id="userName" placeholder="Votre nom" required>
                                <label for="userMail">Votre mail:</label>
                                <input type="email" name="userMail" id="userMail" placeholder="Votre mail" required>
                                <label for="userMessage">Votre message:</label>
                                <textarea name="userMessage" id="userMessage" cols="30" rows="3" placeholder="Votre message"></textarea>
                                <button class="buttonBleuFonce">Envoyer la demande</button>
                            </form>
                        </div>
                    </div>
                </li>