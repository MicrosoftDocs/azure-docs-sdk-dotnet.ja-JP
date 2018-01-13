<Type Name="IServiceRemotingResponseMessageHeader" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageHeader">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingResponseMessageHeader" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingResponseMessageHeader" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageHeader" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingResponseMessageHeader" />
  <TypeSignature Language="F#" Value="type IServiceRemotingResponseMessageHeader = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            リモート処理の応答メッセージのヘッダーを指定するために実装する必要があるインターフェイスを定義します。
            
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddHeader">
      <MemberSignature Language="C#" Value="public void AddHeader (string headerName, byte[] headerValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AddHeader(string headerName, unsigned int8[] headerValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageHeader.AddHeader(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddHeader (headerName As String, headerValue As Byte())" />
      <MemberSignature Language="F#" Value="abstract member AddHeader : string * byte[] -&gt; unit" Usage="iServiceRemotingResponseMessageHeader.AddHeader (headerName, headerValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="headerName" Type="System.String" />
        <Parameter Name="headerValue" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="headerName">ヘッダー名。</param>
        <param name="headerValue">ヘッダーの値。</param>
        <summary>
            指定した名前と値を持つ新しいヘッダーを追加します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetHeaderValue">
      <MemberSignature Language="C#" Value="public bool TryGetHeaderValue (string headerName, out byte[] headerValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryGetHeaderValue(string headerName, [out] unsigned int8[]&amp; headerValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageHeader.TryGetHeaderValue(System.String,System.Byte[]@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetHeaderValue (headerName As String, ByRef headerValue As Byte()) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryGetHeaderValue : string *  -&gt; bool" Usage="iServiceRemotingResponseMessageHeader.TryGetHeaderValue (headerName, headerValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="headerName" Type="System.String" />
        <Parameter Name="headerValue" Type="System.Byte[]&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="headerName">ヘッダー名。</param>
        <param name="headerValue">ヘッダーの値。</param>
        <summary>
            指定した名前のヘッダーを取得します。
            </summary>
        <returns>その名前を持つヘッダーが存在する場合は true。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>