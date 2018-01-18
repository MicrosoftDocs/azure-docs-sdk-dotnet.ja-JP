<Type Name="KeyAndSecretDetails" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails">
  <TypeSignature Language="C#" Value="public class KeyAndSecretDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyAndSecretDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyAndSecretDetails" />
  <TypeSignature Language="F#" Value="type KeyAndSecretDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="24556-101">BEK は、bitlocker キーです。</span><span class="sxs-lookup"><span data-stu-id="24556-101">BEK is bitlocker key.</span></span>
            <span data-ttu-id="24556-102">KEK は、BEK 場合は、VM が次の詳細を保存し、暗号化された暗号化キーを示します。</span><span class="sxs-lookup"><span data-stu-id="24556-102">KEK is encryption key for BEK If the VM was encrypted then we will store follwing details :</span></span>
            1. <span data-ttu-id="24556-103">Secret(BEK) - Url バックアップ データ + vaultId です。</span><span class="sxs-lookup"><span data-stu-id="24556-103">Secret(BEK) - Url + Backup Data + vaultId.</span></span>
            2. <span data-ttu-id="24556-104">Key(KEK) - Url バックアップ データ + vaultId です。</span><span class="sxs-lookup"><span data-stu-id="24556-104">Key(KEK) - Url + Backup Data + vaultId.</span></span>
            <span data-ttu-id="24556-105">BEK と KEK できます potentiallty が別の資格情報コンテナーの id を持ちます。</span><span class="sxs-lookup"><span data-stu-id="24556-105">BEK and KEK can potentiallty have different vault ids.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyAndSecretDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="24556-106">KeyAndSecretDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="24556-106">Initializes a new instance of the KeyAndSecretDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyAndSecretDetails (Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails kekDetails = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails bekDetails = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails kekDetails, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails bekDetails) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails.#ctor(Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails,Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails : Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails * Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails (kekDetails, bekDetails)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kekDetails" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails" />
        <Parameter Name="bekDetails" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails" />
      </Parameters>
      <Docs>
        <param name="kekDetails"><span data-ttu-id="24556-107">KEK は BEK の暗号化キーです。</span><span class="sxs-lookup"><span data-stu-id="24556-107">KEK is encryption key for BEK.</span></span></param>
        <param name="bekDetails"><span data-ttu-id="24556-108">BEK は、bitlocker encrpytion キーです。</span><span class="sxs-lookup"><span data-stu-id="24556-108">BEK is bitlocker encrpytion key.</span></span></param>
        <summary>
            <span data-ttu-id="24556-109">KeyAndSecretDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="24556-109">Initializes a new instance of the KeyAndSecretDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BekDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails BekDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails BekDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails.BekDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property BekDetails As BEKDetails" />
      <MemberSignature Language="F#" Value="member this.BekDetails : Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails.BekDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bekDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24556-110">取得または設定 BEK bitlocker encrpytion キーです。</span><span class="sxs-lookup"><span data-stu-id="24556-110">Gets or sets BEK is bitlocker encrpytion key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KekDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails KekDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails KekDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails.KekDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property KekDetails As KEKDetails" />
      <MemberSignature Language="F#" Value="member this.KekDetails : Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails.KekDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kekDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24556-111">取得または設定 KEK BEK の暗号化キーがします。</span><span class="sxs-lookup"><span data-stu-id="24556-111">Gets or sets KEK is encryption key for BEK.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>