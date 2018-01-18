<Type Name="IServiceRemotingContract" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingContract">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingContract" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingContract" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingContract" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingContract" />
  <TypeSignature Language="F#" Value="type IServiceRemotingContract = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ServiceModel.ServiceContract(CallbackContract=typeof(Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingCallbackContract), Namespace="urn:ServiceFabric.Communication")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
               <span data-ttu-id="2365d-101">WCF サービスのリモート処理のコントラクトを定義するインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="2365d-101">Interface that defines the contract for WCF service remoting.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="OneWayMessage">
      <MemberSignature Language="C#" Value="public void OneWayMessage (ArraySegment&lt;byte&gt; messageHeaders, System.Collections.Generic.IEnumerable&lt;ArraySegment&lt;byte&gt;&gt; requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void OneWayMessage(valuetype System.ArraySegment`1&lt;unsigned int8&gt; messageHeaders, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingContract.OneWayMessage(System.ArraySegment{System.Byte},System.Collections.Generic.IEnumerable{System.ArraySegment{System.Byte}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub OneWayMessage (messageHeaders As ArraySegment(Of Byte), requestBody As IEnumerable(Of ArraySegment(Of Byte)))" />
      <MemberSignature Language="F#" Value="abstract member OneWayMessage : ArraySegment&lt;byte&gt; * seq&lt;ArraySegment&lt;byte&gt;&gt; -&gt; unit" Usage="iServiceRemotingContract.OneWayMessage (messageHeaders, requestBody)" />
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
        <Parameter Name="messageHeaders" Type="System.ArraySegment&lt;System.Byte&gt;" />
        <Parameter Name="requestBody" Type="System.Collections.Generic.IEnumerable&lt;System.ArraySegment&lt;System.Byte&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="messageHeaders"><span data-ttu-id="2365d-102">メッセージ ヘッダーには、要求を逆シリアル化して、サービスにメッセージをディスパッチするために必要な情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="2365d-102">Message Headers contains the information needed to deserialize request and to dispatch message to the service.</span></span></param>
        <param name="requestBody"> <span data-ttu-id="2365d-103">メッセージ本文には、シリアル化されたメッセージが含まれています。</span><span class="sxs-lookup"><span data-stu-id="2365d-103">Message Body contains a serialized message</span></span></param>
        <summary>
               <span data-ttu-id="2365d-104">一方向のメッセージをクライアントに送信します。</span><span class="sxs-lookup"><span data-stu-id="2365d-104">Sends a one way message to the client.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestResponseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.ResponseMessage&gt; RequestResponseAsync (ArraySegment&lt;byte&gt; messageHeaders, System.Collections.Generic.IEnumerable&lt;ArraySegment&lt;byte&gt;&gt; requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.ResponseMessage&gt; RequestResponseAsync(valuetype System.ArraySegment`1&lt;unsigned int8&gt; messageHeaders, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingContract.RequestResponseAsync(System.ArraySegment{System.Byte},System.Collections.Generic.IEnumerable{System.ArraySegment{System.Byte}})" />
      <MemberSignature Language="VB.NET" Value="Public Function RequestResponseAsync (messageHeaders As ArraySegment(Of Byte), requestBody As IEnumerable(Of ArraySegment(Of Byte))) As Task(Of ResponseMessage)" />
      <MemberSignature Language="F#" Value="abstract member RequestResponseAsync : ArraySegment&lt;byte&gt; * seq&lt;ArraySegment&lt;byte&gt;&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.ResponseMessage&gt;" Usage="iServiceRemotingContract.RequestResponseAsync (messageHeaders, requestBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ServiceModel.FaultContract(typeof(Microsoft.ServiceFabric.Services.Remoting.V2.RemoteException))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.ServiceModel.OperationContract</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.ResponseMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageHeaders" Type="System.ArraySegment&lt;System.Byte&gt;" />
        <Parameter Name="requestBody" Type="System.Collections.Generic.IEnumerable&lt;System.ArraySegment&lt;System.Byte&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="messageHeaders"><span data-ttu-id="2365d-105">メッセージ ヘッダーには、要求を逆シリアル化して、サービスにメッセージをディスパッチするために必要な情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="2365d-105">Message Headers contains the information needed to deserialize request and to dispatch message to the service.</span></span></param>
        <param name="requestBody"> <span data-ttu-id="2365d-106">メッセージ本文には、シリアル化された形式で要求が含まれています。</span><span class="sxs-lookup"><span data-stu-id="2365d-106">Message Body contains a request in a serialized form.</span></span></param>
        <summary>
               <span data-ttu-id="2365d-107">クライアントにメッセージを送信し、応答を取得します。</span><span class="sxs-lookup"><span data-stu-id="2365d-107">Sends a message to the client and gets the response.</span></span>
            </summary>
        <returns><span data-ttu-id="2365d-108">応答本文は、クライアントによってシリアル化された応答 recived です。</span><span class="sxs-lookup"><span data-stu-id="2365d-108">Response Body is a serialized response recived by the client</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>