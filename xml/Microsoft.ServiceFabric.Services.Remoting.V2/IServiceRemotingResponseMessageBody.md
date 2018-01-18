<Type Name="IServiceRemotingResponseMessageBody" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingResponseMessageBody" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingResponseMessageBody" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingResponseMessageBody" />
  <TypeSignature Language="F#" Value="type IServiceRemotingResponseMessageBody = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0a2b6-101">リモート処理要求の応答メッセージの本文を提供するために実装する必要があります、インターフェイスを定義します。</span><span class="sxs-lookup"><span data-stu-id="0a2b6-101">Defines the interface that must be implemented to provide Response Message Body for remoting requests .</span></span>
            <span data-ttu-id="0a2b6-102">これには、リモート メソッドの戻り値の型が含まれています。</span><span class="sxs-lookup"><span data-stu-id="0a2b6-102">This contains the return Type of a remoting Method.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public object Get (Type paramType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object Get(class System.Type paramType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody.Get(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Function Get (paramType As Type) As Object" />
      <MemberSignature Language="F#" Value="abstract member Get : Type -&gt; obj" Usage="iServiceRemotingResponseMessageBody.Get paramType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="paramType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="paramType"> <span data-ttu-id="0a2b6-103">リモート処理メソッドの戻り値の型</span><span class="sxs-lookup"><span data-stu-id="0a2b6-103">Return Type of a Remoting Method</span></span></param>
        <summary>
            <span data-ttu-id="0a2b6-104">クライアントに送信する前に、リモート処理応答の本体からリモート メソッドの応答を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a2b6-104">Gets the response of a remoting Method from a remoting response body before sending it to Client.</span></span> 
            </summary>
        <returns><span data-ttu-id="0a2b6-105">リモート処理のメソッドの応答</span><span class="sxs-lookup"><span data-stu-id="0a2b6-105">Remoting Method Response</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Set">
      <MemberSignature Language="C#" Value="public void Set (object response);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Set(object response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody.Set(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Set (response As Object)" />
      <MemberSignature Language="F#" Value="abstract member Set : obj -&gt; unit" Usage="iServiceRemotingResponseMessageBody.Set response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="0a2b6-106">リモート処理のメソッドの応答</span><span class="sxs-lookup"><span data-stu-id="0a2b6-106">Remoting Method Response</span></span></param>
        <summary>
            <span data-ttu-id="0a2b6-107">リモート処理の応答本文にリモート メソッドの応答を設定します。</span><span class="sxs-lookup"><span data-stu-id="0a2b6-107">Sets the response of a remoting Method in a remoting response Body</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>