<Type Name="IVirtualMachineExtensionBase" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineExtensionBase : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineExtensionBase implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineExtensionBase&#xA;Implements IHasInner(Of VirtualMachineExtensionInner)" />
  <TypeSignature Language="F#" Value="type IVirtualMachineExtensionBase = interface&#xA;    interface IHasInner&lt;VirtualMachineExtensionInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            仮想マシンに関連付けられている拡張機能の変更できないクライアント側表現。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AutoUpgradeMinorVersionEnabled">
      <MemberSignature Language="C#" Value="public bool AutoUpgradeMinorVersionEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoUpgradeMinorVersionEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase.AutoUpgradeMinorVersionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoUpgradeMinorVersionEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoUpgradeMinorVersionEnabled : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase.AutoUpgradeMinorVersionEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この拡張機能に基づいている拡張機能のイメージの場合は、新しいマイナー バージョンを公開するときに自動的にアップグレードするこの拡張機能が構成されている場合は true を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            仮想マシンの拡張機能のプロビジョニングの状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,object&gt; PublicSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, object&gt; PublicSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase.PublicSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicSettings As IReadOnlyDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.PublicSettings : System.Collections.Generic.IReadOnlyDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase.PublicSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            キー値のペアとして、仮想マシン拡張機能のパブリック、設定を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicSettingsAsJsonString">
      <MemberSignature Language="C#" Value="public string PublicSettingsAsJsonString { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicSettingsAsJsonString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase.PublicSettingsAsJsonString" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicSettingsAsJsonString As String" />
      <MemberSignature Language="F#" Value="member this.PublicSettingsAsJsonString : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase.PublicSettingsAsJsonString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            JSON 文字列として仮想マシンの拡張機能のパブリック、設定を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublisherName">
      <MemberSignature Language="C#" Value="public string PublisherName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublisherName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase.PublisherName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublisherName As String" />
      <MemberSignature Language="F#" Value="member this.PublisherName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase.PublisherName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この拡張機能が作成された仮想マシン拡張機能のイメージのパブリッシャーの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; Tags { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase.Tags" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tags As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この仮想マシンの拡張機能のタグを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeName">
      <MemberSignature Language="C#" Value="public string TypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TypeName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase.TypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TypeName As String" />
      <MemberSignature Language="F#" Value="member this.TypeName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase.TypeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この拡張機能が作成された仮想マシン拡張機能のイメージの型名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VersionName">
      <MemberSignature Language="C#" Value="public string VersionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VersionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase.VersionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VersionName As String" />
      <MemberSignature Language="F#" Value="member this.VersionName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionBase.VersionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この拡張機能が作成された仮想マシン拡張機能のイメージのバージョン名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>