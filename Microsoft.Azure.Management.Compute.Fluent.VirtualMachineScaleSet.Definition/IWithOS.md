<Type Name="IWithOS" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS">
  <TypeSignature Language="C#" Value="public interface IWithOS" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithOS" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithOS" />
  <TypeSignature Language="F#" Value="type IWithOS = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            仮想マシンのスケールのステージでは、オペレーティング システム イメージを指定できるように定義を設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithLatestLinuxImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithLatestLinuxImage (string publisher, string offer, string sku);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithLatestLinuxImage(string publisher, string offer, string sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithLatestLinuxImage(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLatestLinuxImage (publisher As String, offer As String, sku As String) As IWithLinuxRootUsernameManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithLatestLinuxImage : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged" Usage="iWithOS.WithLatestLinuxImage (publisher, offer, sku)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher">イメージの発行元。</param>
        <param name="offer">イメージのプラン。</param>
        <param name="sku">イメージの SKU。</param>
        <summary>
            Marketplace Linux イメージの最新バージョンを使用することを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithLatestWindowsImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithLatestWindowsImage (string publisher, string offer, string sku);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithLatestWindowsImage(string publisher, string offer, string sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithLatestWindowsImage(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLatestWindowsImage (publisher As String, offer As String, sku As String) As IWithWindowsAdminUsernameManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithLatestWindowsImage : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged" Usage="iWithOS.WithLatestWindowsImage (publisher, offer, sku)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher">イメージのパブリッシャーを指定します。</param>
        <param name="offer">イメージのオファーを指定します。</param>
        <param name="sku">イメージの SKU を指定します。</param>
        <summary>
            指定した marketplace の Windows イメージの最新バージョンを使用することを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithLinuxCustomImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManaged WithLinuxCustomImage (string customImageId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManaged WithLinuxCustomImage(string customImageId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithLinuxCustomImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxCustomImage (customImageId As String) As IWithLinuxRootUsernameManaged" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxCustomImage : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManaged" Usage="iWithOS.WithLinuxCustomImage customImageId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customImageId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="customImageId">カスタム イメージのリソース ID です。</param>
        <summary>
            使用するには、Linux カスタム イメージの ID を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPopularLinuxImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithPopularLinuxImage (Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage knownImage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithPopularLinuxImage(valuetype Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage knownImage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithPopularLinuxImage(Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPopularLinuxImage (knownImage As KnownLinuxVirtualMachineImage) As IWithLinuxRootUsernameManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithPopularLinuxImage : Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged" Usage="iWithOS.WithPopularLinuxImage knownImage" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="knownImage" Type="Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage" />
      </Parameters>
      <Docs>
        <param name="knownImage">既知のマーケットプレイス イメージです。</param>
        <summary>
            既知の marketplace、仮想マシンのオペレーティング システムとして使用する Linux イメージを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPopularWindowsImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithPopularWindowsImage (Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage knownImage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithPopularWindowsImage(valuetype Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage knownImage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithPopularWindowsImage(Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPopularWindowsImage (knownImage As KnownWindowsVirtualMachineImage) As IWithWindowsAdminUsernameManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithPopularWindowsImage : Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged" Usage="iWithOS.WithPopularWindowsImage knownImage" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="knownImage" Type="Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage" />
      </Parameters>
      <Docs>
        <param name="knownImage">既知のマーケットプレイス イメージです。</param>
        <summary>
            スケール セット内の仮想マシンのオペレーティング システムとして使用される既知の marketplace Windows イメージを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithSpecificLinuxImageVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithSpecificLinuxImageVersion (Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference imageReference);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithSpecificLinuxImageVersion(class Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference imageReference) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithSpecificLinuxImageVersion(Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference)" />
      <MemberSignature Language="F#" Value="abstract member WithSpecificLinuxImageVersion : Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged" Usage="iWithOS.WithSpecificLinuxImageVersion imageReference" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference" />
      </Parameters>
      <Docs>
        <param name="imageReference">パブリッシャー、プラン、SKU、および市場インプレース イメージのバージョンについて説明します。</param>
        <summary>
            特定のバージョンのために使用される marketplace に Linux イメージを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithSpecificWindowsImageVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithSpecificWindowsImageVersion (Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference imageReference);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithSpecificWindowsImageVersion(class Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference imageReference) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithSpecificWindowsImageVersion(Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference)" />
      <MemberSignature Language="F#" Value="abstract member WithSpecificWindowsImageVersion : Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged" Usage="iWithOS.WithSpecificWindowsImageVersion imageReference" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference" />
      </Parameters>
      <Docs>
        <param name="imageReference">パブリッシャー、プラン、SKU、および marketplace イメージのバージョンについて説明します。</param>
        <summary>
            Windows イメージを使用する必要があります marketplace の特定のバージョンを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithStoredLinuxImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameUnmanaged WithStoredLinuxImage (string imageUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameUnmanaged WithStoredLinuxImage(string imageUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithStoredLinuxImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStoredLinuxImage (imageUrl As String) As IWithLinuxRootUsernameUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithStoredLinuxImage : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameUnmanaged" Usage="iWithOS.WithStoredLinuxImage imageUrl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageUrl">URL の VHD。</param>
        <summary>
            仮想マシンのオペレーティング システムとして使用されるユーザー (カスタム) Linux イメージを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithStoredWindowsImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameUnmanaged WithStoredWindowsImage (string imageUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameUnmanaged WithStoredWindowsImage(string imageUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithStoredWindowsImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStoredWindowsImage (imageUrl As String) As IWithWindowsAdminUsernameUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithStoredWindowsImage : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameUnmanaged" Usage="iWithOS.WithStoredWindowsImage imageUrl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageUrl">VHD の URL です。</param>
        <summary>
            仮想マシン スケール セット内のオペレーティング システムとして使用するユーザー (カスタム) の Windows イメージを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsCustomImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManaged WithWindowsCustomImage (string customImageId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManaged WithWindowsCustomImage(string customImageId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithWindowsCustomImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsCustomImage (customImageId As String) As IWithWindowsAdminUsernameManaged" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsCustomImage : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManaged" Usage="iWithOS.WithWindowsCustomImage customImageId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customImageId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="customImageId">カスタム イメージのリソース ID です。</param>
        <summary>
            使用するには、Windows のカスタム イメージの ID を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>