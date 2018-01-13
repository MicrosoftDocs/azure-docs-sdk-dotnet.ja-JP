<Type Name="ICanonicalizer" FullName="Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer">
  <TypeSignature Language="C#" Value="public interface ICanonicalizer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICanonicalizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICanonicalizer" />
  <TypeSignature Language="F#" Value="type ICanonicalizer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>HTTP 要求データを署名するための適切な標準形式に変換するカノニカライザーを表します。</para>
      <para>要求を認証する方法の詳細については、次を参照してください。 <see href="http://msdn.microsoft.com/en-us/library/windowsazure/dd179428.aspx">Microsoft Azure ストレージ サービスの認証</see>です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AuthorizationScheme">
      <MemberSignature Language="C#" Value="public string AuthorizationScheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer.AuthorizationScheme" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthorizationScheme As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationScheme : string" Usage="Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer.AuthorizationScheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            正規化に使用する認証スキームを取得します。
            </summary>
        <value>正規化に使用する認証スキームです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanonicalizeHttpRequest">
      <MemberSignature Language="C#" Value="public string CanonicalizeHttpRequest (System.Net.HttpWebRequest request, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string CanonicalizeHttpRequest(class System.Net.HttpWebRequest request, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer.CanonicalizeHttpRequest(System.Net.HttpWebRequest,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CanonicalizeHttpRequest (request As HttpWebRequest, accountName As String) As String" />
      <MemberSignature Language="F#" Value="abstract member CanonicalizeHttpRequest : System.Net.HttpWebRequest * string -&gt; string" Usage="iCanonicalizer.CanonicalizeHttpRequest (request, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.HttpWebRequest" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="request">HTTP 要求に署名する必要があります。</param>
        <param name="accountName">HTTP 要求にアクセスするストレージ アカウントの名前。</param>
        <summary>
            指定された HTTP 要求データを署名するための適切な標準形式に変換します。
            </summary>
        <returns>署名するための適切な標準形式の HTTP 要求データを含む正規化文字列です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>