<Type Name="IServiceRemotingContract" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingContract">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingContract" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingContract" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingContract" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingContract" />
  <TypeSignature Language="F#" Value="type IServiceRemotingContract = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ServiceModel.ServiceContract(CallbackContract=typeof(Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingCallbackContract), Namespace="urn:ServiceFabric.Communication")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
               WCF サービスのリモート処理のコントラクトを定義するインターフェイスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="OneWayMessage">
      <MemberSignature Language="C#" Value="public void OneWayMessage (Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, byte[] requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void OneWayMessage(class Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, unsigned int8[] requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingContract.OneWayMessage(Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub OneWayMessage (messageHeaders As ServiceRemotingMessageHeaders, requestBody As Byte())" />
      <MemberSignature Language="F#" Value="abstract member OneWayMessage : Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders * byte[] -&gt; unit" Usage="iServiceRemotingContract.OneWayMessage (messageHeaders, requestBody)" />
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
        <param name="messageHeaders">メッセージ ヘッダーには、要求を逆シリアル化して、サービスにメッセージをディスパッチするために必要な情報が含まれています。</param>
        <param name="requestBody"> メッセージ本文には、シリアル化されたメッセージが含まれています。</param>
        <summary>
               一方向のメッセージをクライアントに送信します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestResponseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; RequestResponseAsync (Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, byte[] requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; RequestResponseAsync(class Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, unsigned int8[] requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.IServiceRemotingContract.RequestResponseAsync(Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function RequestResponseAsync (messageHeaders As ServiceRemotingMessageHeaders, requestBody As Byte()) As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member RequestResponseAsync : Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders * byte[] -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="iServiceRemotingContract.RequestResponseAsync (messageHeaders, requestBody)" />
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
        <param name="messageHeaders">メッセージ ヘッダーには、要求を逆シリアル化して、サービスにメッセージをディスパッチするために必要な情報が含まれています。</param>
        <param name="requestBody"> メッセージ本文には、シリアル化された形式で要求が含まれています。</param>
        <summary>
               クライアントにメッセージを送信し、応答を取得します。
            </summary>
        <returns>応答本文では、クライアントによって受信されたシリアル化された応答を示します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>