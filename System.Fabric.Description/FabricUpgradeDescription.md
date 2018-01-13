<Type Name="FabricUpgradeDescription" FullName="System.Fabric.Description.FabricUpgradeDescription">
  <TypeSignature Language="C#" Value="public sealed class FabricUpgradeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FabricUpgradeDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.FabricUpgradeDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricUpgradeDescription" />
  <TypeSignature Language="F#" Value="type FabricUpgradeDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="9d0d3-101">Service Fabric アップグレードの詳細をカプセル化するクラスを表します。</span><span class="sxs-lookup"><span data-stu-id="9d0d3-101">Represents a class to encapsulate a Service Fabric upgrade description.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricUpgradeDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.FabricUpgradeDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="9d0d3-102"><see cref="T:System.Fabric.Description.FabricUpgradeDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9d0d3-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.FabricUpgradeDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetCodeVersion">
      <MemberSignature Language="C#" Value="public string TargetCodeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetCodeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.FabricUpgradeDescription.TargetCodeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetCodeVersion As String" />
      <MemberSignature Language="F#" Value="member this.TargetCodeVersion : string with get, set" Usage="System.Fabric.Description.FabricUpgradeDescription.TargetCodeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="9d0d3-103">取得または、Service Fabric アップグレードのターゲット コード バージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="9d0d3-103">Gets or sets the target code version for the Service Fabric upgrade.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="9d0d3-104">Service Fabric アップグレードのターゲット コード バージョンです。</span><span class="sxs-lookup"><span data-stu-id="9d0d3-104">The target code version for the Service Fabric upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetConfigVersion">
      <MemberSignature Language="C#" Value="public string TargetConfigVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetConfigVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.FabricUpgradeDescription.TargetConfigVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetConfigVersion As String" />
      <MemberSignature Language="F#" Value="member this.TargetConfigVersion : string with get, set" Usage="System.Fabric.Description.FabricUpgradeDescription.TargetConfigVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="9d0d3-105">取得または、Service Fabric アップグレードのターゲットの構成バージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="9d0d3-105">Gets or sets the target configuration version for the Service Fabric upgrade.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="9d0d3-106">Service Fabric アップグレードのターゲットの構成のバージョン。</span><span class="sxs-lookup"><span data-stu-id="9d0d3-106">The target configuration version for the Service Fabric upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradePolicyDescription">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.UpgradePolicyDescription UpgradePolicyDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.UpgradePolicyDescription UpgradePolicyDescription" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.FabricUpgradeDescription.UpgradePolicyDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradePolicyDescription As UpgradePolicyDescription" />
      <MemberSignature Language="F#" Value="member this.UpgradePolicyDescription : System.Fabric.Description.UpgradePolicyDescription with get, set" Usage="System.Fabric.Description.FabricUpgradeDescription.UpgradePolicyDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.UpgradePolicyDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="9d0d3-107">取得またはアップグレード ポリシーの説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="9d0d3-107">Gets or sets the upgrade policy description.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="9d0d3-108">アップグレード ポリシーの説明です。</span><span class="sxs-lookup"><span data-stu-id="9d0d3-108">The upgrade policy description.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>