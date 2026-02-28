body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #0f172a;
  color: white;
}

.app {
  text-align: center;
  padding: 20px;
}

.chat-container {
  height: 400px;
  overflow-y: auto;
  border: 1px solid #334155;
  padding: 15px;
  border-radius: 10px;
  background-color: #1e293b;
  margin-bottom: 15px;
}

.message {
  display: flex;
  margin-bottom: 10px;
}

.message.user {
  justify-content: flex-end;
}

.message.assistant {
  justify-content: flex-start;
}

.bubble {
  padding: 10px 15px;
  border-radius: 15px;
  max-width: 60%;
}

.user .bubble {
  background-color: #f97316;
}

.assistant .bubble {
  background-color: #334155;
}

.input-area {
  display: flex;
  justify-content: center;
  gap: 10px;
}

input {
  width: 50%;
  padding: 10px;
  border-radius: 8px;
  border: none;
}

button {
  padding: 10px 15px;
  border-radius: 8px;
  border: none;
  background-color: #f97316;
  color: white;
  cursor: pointer;
}

.metrics {
  margin-top: 20px;
  background: #1e293b;
  padding: 15px;
  border-radius: 10px;
}
