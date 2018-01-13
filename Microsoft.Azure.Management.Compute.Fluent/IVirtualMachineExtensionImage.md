<Type Name="IVirtualMachineExtensionImage" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineExtensionImage : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineExtensionImage implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineExtensionImage&#xA;Implements IHasInner(Of VirtualMachineExtensionImageInner)" />
  <TypeSignature Language="F#" Value="type IVirtualMachineExtensionImage = interface&#xA;    interface IHasInner&lt;VirtualMachineExtensionImageInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionImageInner&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Azure の仮想マシン拡張イメージの変更できないクライアント側表現。
            注: Azure 仮想マシン拡張機能のイメージはバーチャル マシンの拡張機能ハンドラーとも呼ばれます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ComputeRole">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.ComputeRoles ComputeRole { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.ComputeRoles ComputeRole" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.ComputeRole" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputeRole As ComputeRoles" />
      <MemberSignature Language="F#" Value="member this.ComputeRole : Microsoft.Azure.Management.Compute.Fluent.ComputeRoles" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.ComputeRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.ComputeRoles</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この仮想マシン拡張機能のイメージをサポートしているロールの種類を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HandlerSchema">
      <MemberSignature Language="C#" Value="public string HandlerSchema { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HandlerSchema" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.HandlerSchema" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HandlerSchema As String" />
      <MemberSignature Language="F#" Value="member this.HandlerSchema : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.HandlerSchema" />
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
            拡張機能のコンシューマーが一致するスキーマの設定を指定する必要があります、発行元によって定義されたスキーマを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.Id" />
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
            拡張機能のイメージのリソース ID を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OSType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OSType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.OSType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSType As OperatingSystemTypes" />
      <MemberSignature Language="F#" Value="member this.OSType : Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.OSType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この仮想マシン拡張機能のイメージがサポートするオペレーティング システムを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublisherName">
      <MemberSignature Language="C#" Value="public string PublisherName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublisherName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.PublisherName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublisherName As String" />
      <MemberSignature Language="F#" Value="member this.PublisherName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.PublisherName" />
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
            仮想マシン拡張機能のイメージのパブリッシャーの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegionName">
      <MemberSignature Language="C#" Value="public string RegionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.RegionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegionName As String" />
      <MemberSignature Language="F#" Value="member this.RegionName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.RegionName" />
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
            どの仮想マシン拡張機能のイメージが使用可能な領域を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportsMultipleExtensions">
      <MemberSignature Language="C#" Value="public bool SupportsMultipleExtensions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportsMultipleExtensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.SupportsMultipleExtensions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SupportsMultipleExtensions As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportsMultipleExtensions : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.SupportsMultipleExtensions" />
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
            ハンドラーは、複数の拡張機能をサポートできる場合は true を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportsVirtualMachineScaleSets">
      <MemberSignature Language="C#" Value="public bool SupportsVirtualMachineScaleSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportsVirtualMachineScaleSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.SupportsVirtualMachineScaleSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SupportsVirtualMachineScaleSets As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportsVirtualMachineScaleSets : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.SupportsVirtualMachineScaleSets" />
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
            拡張機能を使用できる場合、仮想マシン スケール セットで false それ以外の場合は true を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeName">
      <MemberSignature Language="C#" Value="public string TypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TypeName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.TypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TypeName As String" />
      <MemberSignature Language="F#" Value="member this.TypeName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.TypeName" />
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
            仮想マシン拡張機能のイメージの種類に属しているこのイメージの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As IVirtualMachineExtensionImageVersion" />
      <MemberSignature Language="F#" Value="member this.Version : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImageVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このイメージが属する仮想マシン拡張機能のイメージ バージョンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VersionName">
      <MemberSignature Language="C#" Value="public string VersionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VersionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.VersionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VersionName As String" />
      <MemberSignature Language="F#" Value="member this.VersionName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage.VersionName" />
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
            このイメージを表す仮想マシン拡張機能のイメージ バージョンの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>