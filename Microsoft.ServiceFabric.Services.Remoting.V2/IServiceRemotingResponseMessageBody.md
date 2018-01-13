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
            リモート処理要求の応答メッセージの本文を提供するために実装する必要があります、インターフェイスを定義します。
            これには、リモート メソッドの戻り値の型が含まれています。
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
        <param name="paramType"> リモート処理メソッドの戻り値の型</param>
        <summary>
            クライアントに送信する前に、リモート処理応答の本体からリモート メソッドの応答を取得します。 
            </summary>
        <returns>リモート処理のメソッドの応答</returns>
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
        <param name="response">リモート処理のメソッドの応答</param>
        <summary>
            リモート処理の応答本文にリモート メソッドの応答を設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>