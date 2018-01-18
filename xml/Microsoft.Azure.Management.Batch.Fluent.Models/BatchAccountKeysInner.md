<Type Name="BatchAccountKeysInner" FullName="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner">
  <TypeSignature Language="C#" Value="public class BatchAccountKeysInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchAccountKeysInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchAccountKeysInner" />
  <TypeSignature Language="F#" Value="type BatchAccountKeysInner = class" />
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
            <span data-ttu-id="5af9f-101">Azure Batch アカウント キーのセット。</span><span class="sxs-lookup"><span data-stu-id="5af9f-101">A set of Azure Batch account keys.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountKeysInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5af9f-102">BatchAccountKeysInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5af9f-102">Initializes a new instance of the BatchAccountKeysInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountKeysInner (string accountName = null, string primary = null, string secondary = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, string primary, string secondary) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional accountName As String = null, Optional primary As String = null, Optional secondary As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner : string * string * string -&gt; Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner" Usage="new Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner (accountName, primary, secondary)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="primary" Type="System.String" />
        <Parameter Name="secondary" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName">To be added.</param>
        <param name="primary">To be added.</param>
        <param name="secondary">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accountName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Primary">
      <MemberSignature Language="C#" Value="public string Primary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Primary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner.Primary" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Primary As String" />
      <MemberSignature Language="F#" Value="member this.Primary : string" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner.Primary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5af9f-103">取得またはアカウントに関連付けられている主キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="5af9f-103">Gets or sets the primary key associated with the account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Secondary">
      <MemberSignature Language="C#" Value="public string Secondary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Secondary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner.Secondary" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Secondary As String" />
      <MemberSignature Language="F#" Value="member this.Secondary : string" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner.Secondary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5af9f-104">取得またはアカウントに関連付けられたセカンダリ キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="5af9f-104">Gets or sets the secondary key associated with the account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>