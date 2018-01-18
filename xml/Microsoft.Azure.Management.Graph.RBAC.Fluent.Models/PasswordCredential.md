<Type Name="PasswordCredential" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential">
  <TypeSignature Language="C#" Value="public class PasswordCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PasswordCredential extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class PasswordCredential" />
  <TypeSignature Language="F#" Value="type PasswordCredential = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="78417-101">Active Directory パスワードの資格情報の情報です。</span><span class="sxs-lookup"><span data-stu-id="78417-101">Active Directory Password Credential information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PasswordCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="78417-102">PasswordCredential クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="78417-102">Initializes a new instance of the PasswordCredential class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PasswordCredential (string customKeyIdentifier = null, Nullable&lt;DateTime&gt; startDate = null, Nullable&lt;DateTime&gt; endDate = null, string keyId = null, string value = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string customKeyIdentifier, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endDate, string keyId, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential.#ctor(System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional customKeyIdentifier As String = null, Optional startDate As Nullable(Of DateTime) = null, Optional endDate As Nullable(Of DateTime) = null, Optional keyId As String = null, Optional value As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential : string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential (customKeyIdentifier, startDate, endDate, keyId, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="customKeyIdentifier" Type="System.String" />
        <Parameter Name="startDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="keyId" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="customKeyIdentifier">To be added.</param>
        <param name="startDate">To be added.</param>
        <param name="endDate">To be added.</param>
        <param name="keyId">To be added.</param>
        <param name="value">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomKeyIdentifier">
      <MemberSignature Language="C#" Value="public string CustomKeyIdentifier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomKeyIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential.CustomKeyIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomKeyIdentifier As String" />
      <MemberSignature Language="F#" Value="member this.CustomKeyIdentifier : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential.CustomKeyIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="customKeyIdentifier")</AttributeName>
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
    <Member MemberName="EndDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential.EndDate" />
      <MemberSignature Language="VB.NET" Value="Public Property EndDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential.EndDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="78417-103">取得または終了日を設定します。</span><span class="sxs-lookup"><span data-stu-id="78417-103">Gets or sets end date.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyId">
      <MemberSignature Language="C#" Value="public string KeyId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential.KeyId" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyId As String" />
      <MemberSignature Language="F#" Value="member this.KeyId : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential.KeyId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="78417-104">取得または設定キーの id。</span><span class="sxs-lookup"><span data-stu-id="78417-104">Gets or sets key ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential.StartDate" />
      <MemberSignature Language="VB.NET" Value="Public Property StartDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential.StartDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="78417-105">取得または開始日を設定します。</span><span class="sxs-lookup"><span data-stu-id="78417-105">Gets or sets start date.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="78417-106">取得またはキーの値を設定します。</span><span class="sxs-lookup"><span data-stu-id="78417-106">Gets or sets key value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>