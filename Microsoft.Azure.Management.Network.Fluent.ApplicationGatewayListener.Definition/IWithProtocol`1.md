<Type Name="IWithProtocol&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithProtocol&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithProtocol&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithProtocol`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithProtocol`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithProtocol(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithProtocol&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るには、親アプリケーション ゲートウェイ定義の段階です。</typeparam>
    <summary>
            プロトコルを指定できるようにアプリケーション ゲートウェイ フロント エンド リスナー定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithHttp">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;ParentT&gt; WithHttp ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach`1&lt;!ParentT&gt; WithHttp() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithProtocol`1.WithHttp" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttp () As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHttp : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithProtocol.WithHttp " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            HTTP プロトコルのリスナーであることを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttps">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithSslCertificate&lt;ParentT&gt; WithHttps ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithSslCertificate`1&lt;!ParentT&gt; WithHttps() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithProtocol`1.WithHttps" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttps () As IWithSslCertificate(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHttps : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithSslCertificate&lt;'ParentT&gt;" Usage="iWithProtocol.WithHttps " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithSslCertificate&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            HTTPS プロトコルのリスナーであることを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>