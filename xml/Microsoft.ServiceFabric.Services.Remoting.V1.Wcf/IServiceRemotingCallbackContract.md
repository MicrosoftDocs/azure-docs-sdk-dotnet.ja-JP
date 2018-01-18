<Type Name="IServiceRemotingCallbackContract" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingCallbackContract">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingCallbackContract" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingCallbackContract" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingCallbackContract" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingCallbackContract" />
  <TypeSignature Language="F#" Value="type IServiceRemotingCallbackContract = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ServiceModel.ServiceContract(Namespace="urn:ServiceFabric.Communication")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
             <span data-ttu-id="c924a-101">Wcf リモート処理リスナーからクライアントにコールバック機構を提供するために実装する必要がありますのあるインターフェイスを定義します。</span><span class="sxs-lookup"><span data-stu-id="c924a-101">Defines the interface that must be implemented for providing callback mechanism from the wcf remoting listener to the client.</span></span>
             </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="RequestResponseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; RequestResponseAsync (Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, byte[] requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; RequestResponseAsync(class Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, unsigned int8[] requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingCallbackContract.RequestResponseAsync(Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function RequestResponseAsync (messageHeaders As ServiceRemotingMessageHeaders, requestBody As Byte()) As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member RequestResponseAsync : Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders * byte[] -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="iServiceRemotingCallbackContract.RequestResponseAsync (messageHeaders, requestBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ServiceModel.FaultContract(typeof(Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.ServiceModel.OperationContract</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageHeaders" Type="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders" />
        <Parameter Name="requestBody" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="messageHeaders"><span data-ttu-id="c924a-102">メッセージ ヘッダーには、要求を逆シリアル化して、クライアントにメッセージをディスパッチするために必要な情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c924a-102">Message Headers contains the information needed to deserialize request and to dispatch message to the client.</span></span></param>
        <param name="requestBody"> <span data-ttu-id="c924a-103">メッセージ本文には、シリアル化された形式で要求が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c924a-103">Message Body contains a request in a serialized form.</span></span></param>
        <summary>
             <span data-ttu-id="c924a-104">クライアントにメッセージを送信し、応答を取得します。</span><span class="sxs-lookup"><span data-stu-id="c924a-104">Sends a message to the client and gets the response.</span></span>
            </summary>
        <returns><span data-ttu-id="c924a-105">応答本文では、サービスによって受信されたシリアル化された応答を示します。</span><span class="sxs-lookup"><span data-stu-id="c924a-105">Response Body is a serialized response received by the service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendOneWay">
      <MemberSignature Language="C#" Value="public void SendOneWay (Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, byte[] requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SendOneWay(class Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, unsigned int8[] requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingCallbackContract.SendOneWay(Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub SendOneWay (messageHeaders As ServiceRemotingMessageHeaders, requestBody As Byte())" />
      <MemberSignature Language="F#" Value="abstract member SendOneWay : Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders * byte[] -&gt; unit" Usage="iServiceRemotingCallbackContract.SendOneWay (messageHeaders, requestBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ServiceModel.OperationContract(IsOneWay=true)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageHeaders" Type="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders" />
        <Parameter Name="requestBody" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="messageHeaders"><span data-ttu-id="c924a-106">メッセージ ヘッダーには、要求を逆シリアル化して、クライアントにメッセージをディスパッチするために必要な情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c924a-106">Message Headers contains the information needed to deserialize request and to dispatch message to the client.</span></span></param>
        <param name="requestBody"> <span data-ttu-id="c924a-107">メッセージ本文には、シリアル化された形式で要求が含まれています。</span><span class="sxs-lookup"><span data-stu-id="c924a-107">Message Body contains a request in a serialized form.</span></span></param>
        <summary>
            <span data-ttu-id="c924a-108">一方向のメッセージをクライアントに送信します。</span><span class="sxs-lookup"><span data-stu-id="c924a-108">Sends a one way message to the client.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>