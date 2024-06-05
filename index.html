const axios = require('axios');

module.exports = async (req, res) => {
    if (req.method !== 'POST') {
        return res.status(405).json({ message: 'Method Not Allowed' });
    }

    const targetWebhookUrl = process.env.LB_WEBHOOK_URL; // Make a env file with WEBHOOK_URL var.

    try {
        const payload = req.body;

        await axios.post(targetWebhookUrl, payload);

        res.status(200).json({ message: 'Payload forwarded successfully' });
    } catch (error) {
        console.error('Error forwarding payload:', error);
        res.status(500).json({ message: 'Error forwarding payload' });
    }
};
