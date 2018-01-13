<Type Name="OperationStatusJobsExtendedInfo" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusJobsExtendedInfo">
  <TypeSignature Language="C#" Value="public class OperationStatusJobsExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusExtendedInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationStatusJobsExtendedInfo extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusExtendedInfo" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusJobsExtendedInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationStatusJobsExtendedInfo&#xA;Inherits OperationStatusExtendedInfo" />
  <TypeSignature Language="F#" Value="type OperationStatusJobsExtendedInfo = class&#xA;    inherit OperationStatusExtendedInfo" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusExtendedInfo</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ecaae-101">操作の状態は、ジョブの一覧の情報を拡張します。</span><span class="sxs-lookup"><span data-stu-id="ecaae-101">Operation status extended info for list of jobs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationStatusJobsExtendedInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusJobsExtendedInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ecaae-102">OperationStatusJobsExtendedInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ecaae-102">Initializes a new instance of the OperationStatusJobsExtendedInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationStatusJobsExtendedInfo (System.Collections.Generic.IList&lt;string&gt; jobIds = null, System.Collections.Generic.IDictionary&lt;string,string&gt; failedJobsError = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; jobIds, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; failedJobsError) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusJobsExtendedInfo.#ctor(System.Collections.Generic.IList{System.String},System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional jobIds As IList(Of String) = null, Optional failedJobsError As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusJobsExtendedInfo : System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusJobsExtendedInfo" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusJobsExtendedInfo (jobIds, failedJobsError)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="failedJobsError" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="jobIds"><span data-ttu-id="ecaae-103">保護されたアイテムに対して作成されたジョブの Id。</span><span class="sxs-lookup"><span data-stu-id="ecaae-103">IDs of the jobs created for the protected item.</span></span></param>
        <param name="failedJobsError"><span data-ttu-id="ecaae-104">対応するエラー コードと共にすべての失敗したジョブを格納します。</span><span class="sxs-lookup"><span data-stu-id="ecaae-104">Stores all the failed jobs along with the corresponding error codes.</span></span></param>
        <summary>
            <span data-ttu-id="ecaae-105">OperationStatusJobsExtendedInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ecaae-105">Initializes a new instance of the OperationStatusJobsExtendedInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailedJobsError">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; FailedJobsError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; FailedJobsError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusJobsExtendedInfo.FailedJobsError" />
      <MemberSignature Language="VB.NET" Value="Public Property FailedJobsError As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.FailedJobsError : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusJobsExtendedInfo.FailedJobsError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failedJobsError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecaae-106">取得または設定は、対応するエラー コードと共にすべての失敗したジョブを格納します。</span><span class="sxs-lookup"><span data-stu-id="ecaae-106">Gets or sets stores all the failed jobs along with the corresponding error codes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; JobIds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; JobIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusJobsExtendedInfo.JobIds" />
      <MemberSignature Language="VB.NET" Value="Public Property JobIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.JobIds : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusJobsExtendedInfo.JobIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobIds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecaae-107">取得または保護されたアイテムに対して作成されたジョブの Id を設定します。</span><span class="sxs-lookup"><span data-stu-id="ecaae-107">Gets or sets iDs of the jobs created for the protected item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>