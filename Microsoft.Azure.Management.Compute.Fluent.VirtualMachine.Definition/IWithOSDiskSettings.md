<Type Name="IWithOSDiskSettings" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOSDiskSettings">
  <TypeSignature Language="C#" Value="public interface IWithOSDiskSettings" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithOSDiskSettings" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOSDiskSettings" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithOSDiskSettings" />
  <TypeSignature Language="F#" Value="type IWithOSDiskSettings = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c42ad-101">OS ディスク構成を指定できるように、仮想マシンの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="c42ad-101">The stage of a virtual machine definition allowing to specify OS disk configurations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithOSDiskCaching">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithOSDiskCaching (Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithOSDiskCaching(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOSDiskSettings.WithOSDiskCaching(Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSDiskCaching (cachingType As CachingTypes) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithOSDiskCaching : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithOSDiskSettings.WithOSDiskCaching cachingType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="cachingType"><span data-ttu-id="c42ad-102">キャッシュの型。</span><span class="sxs-lookup"><span data-stu-id="c42ad-102">A caching type.</span></span></param>
        <summary>
            <span data-ttu-id="c42ad-103">OS ディスクのキャッシュの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="c42ad-103">Specifies the caching type for the OS disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c42ad-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c42ad-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithOSDiskEncryptionSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithOSDiskEncryptionSettings (Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithOSDiskEncryptionSettings(class Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOSDiskSettings.WithOSDiskEncryptionSettings(Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSDiskEncryptionSettings (settings As DiskEncryptionSettings) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithOSDiskEncryptionSettings : Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithOSDiskSettings.WithOSDiskEncryptionSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings" />
      </Parameters>
      <Docs>
        <param name="settings"><span data-ttu-id="c42ad-105">暗号化の設定。</span><span class="sxs-lookup"><span data-stu-id="c42ad-105">The encryption settings.</span></span></param>
        <summary>
            <span data-ttu-id="c42ad-106">OS ディスクの暗号化の設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="c42ad-106">Specifies the encryption settings for the OS Disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c42ad-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c42ad-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithOSDiskName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithOSDiskName (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithOSDiskName(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOSDiskSettings.WithOSDiskName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSDiskName (name As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithOSDiskName : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithOSDiskSettings.WithOSDiskName name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c42ad-108">OS ディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c42ad-108">An OS disk name.</span></span></param>
        <summary>
            <span data-ttu-id="c42ad-109">OS ディスクの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="c42ad-109">Specifies the name for the OS Disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c42ad-110">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c42ad-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithOSDiskSizeInGB">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithOSDiskSizeInGB (int size);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithOSDiskSizeInGB(int32 size) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOSDiskSettings.WithOSDiskSizeInGB(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSDiskSizeInGB (size As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithOSDiskSizeInGB : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithOSDiskSettings.WithOSDiskSizeInGB size" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="size" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="size"><span data-ttu-id="c42ad-111">VHD のサイズ。</span><span class="sxs-lookup"><span data-stu-id="c42ad-111">The VHD size.</span></span></param>
        <summary>
            <span data-ttu-id="c42ad-112">GB で OSDisk のサイズを指定します。</span><span class="sxs-lookup"><span data-stu-id="c42ad-112">Specifies the size of the OSDisk in GB.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c42ad-113">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c42ad-113">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>