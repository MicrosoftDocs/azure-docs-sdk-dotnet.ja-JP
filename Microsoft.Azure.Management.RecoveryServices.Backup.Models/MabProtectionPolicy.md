<Type Name="MabProtectionPolicy" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabProtectionPolicy">
  <TypeSignature Language="C#" Value="public class MabProtectionPolicy : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MabProtectionPolicy extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabProtectionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class MabProtectionPolicy&#xA;Inherits ProtectionPolicy" />
  <TypeSignature Language="F#" Value="type MabProtectionPolicy = class&#xA;    inherit ProtectionPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("MAB")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e9bbb-101">Mab コンテナーに固有のバックアップ ポリシー。</span><span class="sxs-lookup"><span data-stu-id="e9bbb-101">Mab container-specific backup policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MabProtectionPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabProtectionPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e9bbb-102">MabProtectionPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e9bbb-102">Initializes a new instance of the MabProtectionPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MabProtectionPolicy (Nullable&lt;int&gt; protectedItemsCount = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy schedulePolicy = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy retentionPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; protectedItemsCount, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy schedulePolicy, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy retentionPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabProtectionPolicy.#ctor(System.Nullable{System.Int32},Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy,Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabProtectionPolicy : Nullable&lt;int&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy * Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabProtectionPolicy" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabProtectionPolicy (protectedItemsCount, schedulePolicy, retentionPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protectedItemsCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="schedulePolicy" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy" />
        <Parameter Name="retentionPolicy" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy" />
      </Parameters>
      <Docs>
        <param name="protectedItemsCount"><span data-ttu-id="e9bbb-103">このポリシーに関連付けられている項目の数。</span><span class="sxs-lookup"><span data-stu-id="e9bbb-103">Number of items associated with this policy.</span></span></param>
        <param name="schedulePolicy"><span data-ttu-id="e9bbb-104">バックアップ ポリシーのバックアップのスケジュール。</span><span class="sxs-lookup"><span data-stu-id="e9bbb-104">Backup schedule of backup policy.</span></span></param>
        <param name="retentionPolicy"><span data-ttu-id="e9bbb-105">保有ポリシーの詳細。</span><span class="sxs-lookup"><span data-stu-id="e9bbb-105">Retention policy details.</span></span></param>
        <summary>
            <span data-ttu-id="e9bbb-106">MabProtectionPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e9bbb-106">Initializes a new instance of the MabProtectionPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy RetentionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy RetentionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabProtectionPolicy.RetentionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionPolicy As RetentionPolicy" />
      <MemberSignature Language="F#" Value="member this.RetentionPolicy : Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabProtectionPolicy.RetentionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e9bbb-107">取得または保持ポリシーの詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="e9bbb-107">Gets or sets retention policy details.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchedulePolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy SchedulePolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy SchedulePolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabProtectionPolicy.SchedulePolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property SchedulePolicy As SchedulePolicy" />
      <MemberSignature Language="F#" Value="member this.SchedulePolicy : Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabProtectionPolicy.SchedulePolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schedulePolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e9bbb-108">取得またはバックアップ ポリシーのバックアップのスケジュールを設定します。</span><span class="sxs-lookup"><span data-stu-id="e9bbb-108">Gets or sets backup schedule of backup policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>