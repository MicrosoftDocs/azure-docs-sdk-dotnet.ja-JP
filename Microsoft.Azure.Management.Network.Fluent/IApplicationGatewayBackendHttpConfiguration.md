<Type Name="IApplicationGatewayBackendHttpConfiguration" FullName="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration">
  <TypeSignature Language="C#" Value="public interface IApplicationGatewayBackendHttpConfiguration : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfigurationBeta, Microsoft.Azure.Management.Network.Fluent.IHasPort, Microsoft.Azure.Management.Network.Fluent.IHasProtocol&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProtocol&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IApplicationGatewayBackendHttpConfiguration implements class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfigurationBeta, class Microsoft.Azure.Management.Network.Fluent.IHasPort, class Microsoft.Azure.Management.Network.Fluent.IHasProtocol`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProtocol&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IApplicationGatewayBackendHttpConfiguration&#xA;Implements IApplicationGatewayBackendHttpConfigurationBeta, IBeta, IChildResource(Of IApplicationGateway), IHasInner(Of ApplicationGatewayBackendHttpSettingsInner), IHasParent(Of IApplicationGateway), IHasPort, IHasProtocol(Of ApplicationGatewayProtocol)" />
  <TypeSignature Language="F#" Value="type IApplicationGatewayBackendHttpConfiguration = interface&#xA;    interface IHasInner&lt;ApplicationGatewayBackendHttpSettingsInner&gt;&#xA;    interface IChildResource&lt;IApplicationGateway&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IApplicationGateway&gt;&#xA;    interface IHasProtocol&lt;ApplicationGatewayProtocol&gt;&#xA;    interface IHasPort&#xA;    interface IApplicationGatewayBackendHttpConfigurationBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfigurationBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasPort</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasProtocol&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProtocol&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Application gateway のバックエンド HTTP 構成の変更できないクライアント側表現。
            </summary>
    <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="CookieBasedAffinity">
      <MemberSignature Language="C#" Value="public bool CookieBasedAffinity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CookieBasedAffinity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration.CookieBasedAffinity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CookieBasedAffinity As Boolean" />
      <MemberSignature Language="F#" Value="member this.CookieBasedAffinity : bool" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration.CookieBasedAffinity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Cookie ベースのアフィニティ (スティッキー セッション) 場合は true。 取得が有効になってそれ以外の場合は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Probe">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe Probe { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe Probe" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration.Probe" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Probe As IApplicationGatewayProbe" />
      <MemberSignature Language="F#" Value="member this.Probe : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration.Probe" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestTimeout">
      <MemberSignature Language="C#" Value="public int RequestTimeout { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RequestTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration.RequestTimeout" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.RequestTimeout : int" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration.RequestTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            HTTP 要求のタイムアウトを秒単位で取得します。 指定した時間内に応答を受信しない場合、要求は失敗します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>