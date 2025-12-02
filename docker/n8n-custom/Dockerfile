FROM n8nio/n8n:latest

RUN mkdir -p /home/node/.n8n/custom && \
    cd /home/node/.n8n/custom && \
    npm install https://btcc.s3.dualstack.eu-west-1.amazonaws.com/widget-lab/npm/n8n-nodes-3dxinterfaces/dist/widget-lab-n8n-nodes-3dxinterfaces-0.6.0.tgz

EXPOSE 5678
