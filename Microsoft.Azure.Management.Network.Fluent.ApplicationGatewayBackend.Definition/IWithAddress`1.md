<Type Name="IWithAddress&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAddress&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAddress&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAddress`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAddress`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAddress(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAddress&lt;'ParentT&gt; = interface" />
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
            アプリケーション ゲートウェイ バックエンド定義できるように、バックエンドにアドレスを追加するの段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAttach&lt;ParentT&gt; WithFqdn (string fqdn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAttach`1&lt;!ParentT&gt; WithFqdn(string fqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAddress`1.WithFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFqdn (fqdn As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithFqdn : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAddress.WithFqdn fqdn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fqdn">完全修飾ドメイン名 (FQDN) です。</param>
        <summary>
            バックエンドに指定した既存の完全修飾ドメイン名 (FQDN) を追加します。
            この呼び出しは、複数の Fqdn を追加するシーケンスで実行できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAttach&lt;ParentT&gt; WithIPAddress (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAttach`1&lt;!ParentT&gt; WithIPAddress(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAddress`1.WithIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIPAddress (ipAddress As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAddress.WithIPAddress ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress">IP アドレス。</param>
        <summary>
            バックエンドに指定した既存の IP アドレスを追加します。
            この呼び出しは、複数の IP アドレスを追加するシーケンスで実行できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>