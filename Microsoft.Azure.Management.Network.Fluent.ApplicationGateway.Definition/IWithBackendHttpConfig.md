<Type Name="IWithBackendHttpConfig" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithBackendHttpConfig">
  <TypeSignature Language="C#" Value="public interface IWithBackendHttpConfig" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackendHttpConfig" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithBackendHttpConfig" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackendHttpConfig" />
  <TypeSignature Language="F#" Value="type IWithBackendHttpConfig = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            バックエンド HTTP 設定の追加を許可するアプリケーション ゲートウェイ定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineBackendHttpConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt; DefineBackendHttpConfiguration (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt; DefineBackendHttpConfiguration(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithBackendHttpConfig.DefineBackendHttpConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineBackendHttpConfiguration (name As String) As IBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineBackendHttpConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;" Usage="iWithBackendHttpConfig.DefineBackendHttpConfiguration name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">バックエンド HTTP 設定の一意の名前。</param>
        <summary>
            ゲートウェイに接続する新しいアプリケーション ゲートウェイ バックエンド HTTP 設定の定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>バックエンド HTTP 構成の定義の最初の段階です。</return>
      </Docs>
    </Member>
  </Members>
</Type>