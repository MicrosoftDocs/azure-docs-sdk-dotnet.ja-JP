<Type Name="AzureIaaSVMProtectedItemExtendedInfo" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo">
  <TypeSignature Language="C#" Value="public class AzureIaaSVMProtectedItemExtendedInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureIaaSVMProtectedItemExtendedInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureIaaSVMProtectedItemExtendedInfo" />
  <TypeSignature Language="F#" Value="type AzureIaaSVMProtectedItemExtendedInfo = class" />
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
            <span data-ttu-id="cfb1b-101">Azure IaaS 仮想マシン バックアップ アイテムの特定の詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="cfb1b-101">Additional information on Azure IaaS VM specific backup item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSVMProtectedItemExtendedInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cfb1b-102">AzureIaaSVMProtectedItemExtendedInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cfb1b-102">Initializes a new instance of the AzureIaaSVMProtectedItemExtendedInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSVMProtectedItemExtendedInfo (Nullable&lt;DateTime&gt; oldestRecoveryPoint = null, Nullable&lt;int&gt; recoveryPointCount = null, Nullable&lt;bool&gt; policyInconsistent = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; oldestRecoveryPoint, valuetype System.Nullable`1&lt;int32&gt; recoveryPointCount, valuetype System.Nullable`1&lt;bool&gt; policyInconsistent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo.#ctor(System.Nullable{System.DateTime},System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional oldestRecoveryPoint As Nullable(Of DateTime) = null, Optional recoveryPointCount As Nullable(Of Integer) = null, Optional policyInconsistent As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo : Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo (oldestRecoveryPoint, recoveryPointCount, policyInconsistent)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="oldestRecoveryPoint" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="recoveryPointCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="policyInconsistent" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="oldestRecoveryPoint"><span data-ttu-id="cfb1b-103">このバックアップ項目の使用可能な最も古いバックアップ コピーは、します。</span><span class="sxs-lookup"><span data-stu-id="cfb1b-103">The oldest backup copy available for this backup item.</span></span></param>
        <param name="recoveryPointCount"><span data-ttu-id="cfb1b-104">このバックアップ アイテムのバックアップ コピーの数。</span><span class="sxs-lookup"><span data-stu-id="cfb1b-104">Number of backup copies available for this backup item.</span></span></param>
        <param name="policyInconsistent"><span data-ttu-id="cfb1b-105">バックアップ項目に関連付けられているバックアップ ポリシーを一貫性のあるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="cfb1b-105">Specifies if backup policy associated with the backup item is inconsistent.</span></span></param>
        <summary>
            <span data-ttu-id="cfb1b-106">AzureIaaSVMProtectedItemExtendedInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cfb1b-106">Initializes a new instance of the AzureIaaSVMProtectedItemExtendedInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OldestRecoveryPoint">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OldestRecoveryPoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OldestRecoveryPoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo.OldestRecoveryPoint" />
      <MemberSignature Language="VB.NET" Value="Public Property OldestRecoveryPoint As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OldestRecoveryPoint : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo.OldestRecoveryPoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="oldestRecoveryPoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cfb1b-107">取得またはこのバックアップ項目の使用可能な最も古いバックアップ コピーを設定します。</span><span class="sxs-lookup"><span data-stu-id="cfb1b-107">Gets or sets the oldest backup copy available for this backup item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyInconsistent">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PolicyInconsistent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PolicyInconsistent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo.PolicyInconsistent" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyInconsistent As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PolicyInconsistent : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo.PolicyInconsistent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="policyInconsistent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cfb1b-108">取得または設定は、バックアップの項目に関連付けられているバックアップ ポリシーに整合性がないかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="cfb1b-108">Gets or sets specifies if backup policy associated with the backup item is inconsistent.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPointCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RecoveryPointCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RecoveryPointCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo.RecoveryPointCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryPointCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RecoveryPointCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo.RecoveryPointCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryPointCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cfb1b-109">取得またはこのバックアップ アイテムのバックアップ コピーの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="cfb1b-109">Gets or sets number of backup copies available for this backup item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>