<Type Name="BackupPolicyListResponse" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse">
  <TypeSignature Language="C#" Value="public class BackupPolicyListResponse : Microsoft.Azure.AzureOperationResponse, System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupPolicyListResponse extends Microsoft.Azure.AzureOperationResponse implements class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupPolicyListResponse&#xA;Inherits AzureOperationResponse&#xA;Implements IEnumerable(Of BackupPolicy)" />
  <TypeSignature Language="F#" Value="type BackupPolicyListResponse = class&#xA;    inherit AzureOperationResponse&#xA;    interface seq&lt;BackupPolicy&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.AzureOperationResponse</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="d67da-101">バックアップ ポリシーの一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="d67da-101">The response model for the list of backup policies.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupPolicyListResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d67da-102">BackupPolicyListResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d67da-102">Initializes a new instance of the BackupPolicyListResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy&gt; BackupPolicies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy&gt; BackupPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse.BackupPolicies" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupPolicies As IList(Of BackupPolicy)" />
      <MemberSignature Language="F#" Value="member this.BackupPolicies : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse.BackupPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d67da-103">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d67da-103">Optional.</span></span> <span data-ttu-id="d67da-104">バックアップ ポリシーのコレクション</span><span class="sxs-lookup"><span data-stu-id="d67da-104">The collection of backup policies</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of BackupPolicy)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy&gt;" Usage="backupPolicyListResponse.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d67da-105">BackupPolicies のシーケンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="d67da-105">Gets the sequence of BackupPolicies.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d67da-106">BackupPolicies のシーケンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="d67da-106">Gets the sequence of BackupPolicies.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>