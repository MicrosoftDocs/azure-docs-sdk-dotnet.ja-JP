<Type Name="BatchLocationQuotaInner" FullName="Microsoft.Azure.Management.Batch.Fluent.Models.BatchLocationQuotaInner">
  <TypeSignature Language="C#" Value="public class BatchLocationQuotaInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchLocationQuotaInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.Models.BatchLocationQuotaInner" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchLocationQuotaInner" />
  <TypeSignature Language="F#" Value="type BatchLocationQuotaInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8b161-101">クォータは、特定のサブスクリプションのバッチ処理領域に関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="8b161-101">Quotas associated with a Batch region for a particular subscription.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchLocationQuotaInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.BatchLocationQuotaInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8b161-102">BatchLocationQuotaInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8b161-102">Initializes a new instance of the BatchLocationQuotaInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchLocationQuotaInner (Nullable&lt;int&gt; accountQuota = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; accountQuota) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.BatchLocationQuotaInner.#ctor(System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional accountQuota As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Fluent.Models.BatchLocationQuotaInner : Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Batch.Fluent.Models.BatchLocationQuotaInner" Usage="new Microsoft.Azure.Management.Batch.Fluent.Models.BatchLocationQuotaInner accountQuota" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountQuota" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="accountQuota"><span data-ttu-id="8b161-103">指定した領域で、サブスクリプションで作成されるバッチ アカウントの数。</span><span class="sxs-lookup"><span data-stu-id="8b161-103">The number of Batch accounts that may be created under the subscription in the specified region.</span></span></param>
        <summary>
            <span data-ttu-id="8b161-104">BatchLocationQuotaInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8b161-104">Initializes a new instance of the BatchLocationQuotaInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountQuota">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; AccountQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; AccountQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.BatchLocationQuotaInner.AccountQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountQuota As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.AccountQuota : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.BatchLocationQuotaInner.AccountQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accountQuota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b161-105">取得または指定した領域で、サブスクリプションで作成されるバッチ アカウントの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="8b161-105">Gets or sets the number of Batch accounts that may be created under the subscription in the specified region.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>