<Type Name="IWithIPConfig" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig">
  <TypeSignature Language="C#" Value="public interface IWithIPConfig" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIPConfig" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIPConfig" />
  <TypeSignature Language="F#" Value="type IWithIPConfig = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            アプリケーション ゲートウェイの更新を許可する IP 構成を変更する段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineDefaultIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineDefaultIPConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineDefaultIPConfiguration() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig.DefineDefaultIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineDefaultIPConfiguration () As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineDefaultIPConfiguration : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithIPConfig.DefineDefaultIPConfiguration " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            既定の IP 構成の定義を開始します。
            これに相当がありますが、既定の IP 構成に対して既に存在する場合、<code>updateDefaultIPConfiguration()</code>です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>IP 構成の更新の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateDefaultIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate UpdateDefaultIPConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate UpdateDefaultIPConfiguration() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig.UpdateDefaultIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateDefaultIPConfiguration () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateDefaultIPConfiguration : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate" Usage="iWithIPConfig.UpdateDefaultIPConfiguration " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            既定の IP 構成、1 つしかないと仮定した場合に存在する 1 つだけの IP 構成などの更新を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>IP 構成の更新の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate UpdateIPConfiguration (string ipConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate UpdateIPConfiguration(string ipConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig.UpdateIPConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateIPConfiguration (ipConfigurationName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateIPConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate" Usage="iWithIPConfig.UpdateIPConfiguration ipConfigurationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipConfigurationName">既存の IP 構成の名前。</param>
        <summary>
            既存の IP 構成の更新を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>IP 構成の更新の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutIPConfiguration (string ipConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutIPConfiguration(string ipConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig.WithoutIPConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutIPConfiguration (ipConfigurationName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutIPConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithIPConfig.WithoutIPConfiguration ipConfigurationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipConfigurationName">削除する IP 構成の名前。</param>
        <summary>
            指定された IP 構成を削除します。
            他の設定で参照されている IP 構成を削除すると、アプリケーション ゲートウェイが分割することに注意してください。
            また、関数には、そのアプリケーション ゲートウェイの少なくとも 1 つの IP 構成が必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>