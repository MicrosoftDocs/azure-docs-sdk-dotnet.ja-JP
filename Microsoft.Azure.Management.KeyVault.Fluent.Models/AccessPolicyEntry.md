<Type Name="AccessPolicyEntry" FullName="Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry">
  <TypeSignature Language="C#" Value="public class AccessPolicyEntry" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AccessPolicyEntry extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry" />
  <TypeSignature Language="VB.NET" Value="Public Class AccessPolicyEntry" />
  <TypeSignature Language="F#" Value="type AccessPolicyEntry = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Key vault にアクセスできる id です。 配列内のすべての id は、key vault のテナント ID と同じテナント ID を使用する必要があります。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessPolicyEntry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AccessPolicyEntry クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessPolicyEntry (Guid tenantId, string objectId, Microsoft.Azure.Management.KeyVault.Fluent.Models.Permissions permissions, Nullable&lt;Guid&gt; applicationId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid tenantId, string objectId, class Microsoft.Azure.Management.KeyVault.Fluent.Models.Permissions permissions, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; applicationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry.#ctor(System.Guid,System.String,Microsoft.Azure.Management.KeyVault.Fluent.Models.Permissions,System.Nullable{System.Guid})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry : Guid * string * Microsoft.Azure.Management.KeyVault.Fluent.Models.Permissions * Nullable&lt;Guid&gt; -&gt; Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry" Usage="new Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry (tenantId, objectId, permissions, applicationId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tenantId" Type="System.Guid" />
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="permissions" Type="Microsoft.Azure.Management.KeyVault.Fluent.Models.Permissions" />
        <Parameter Name="applicationId" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="tenantId">Key vault への要求の認証に使用する Azure Active Directory テナント ID です。</param>
        <param name="objectId">ユーザー、サービス プリンシパルまたはコンテナーの Azure Active Directory テナントのセキュリティ グループのオブジェクト ID。 オブジェクト ID は、アクセス ポリシーの一覧については一意である必要があります。</param>
        <param name="permissions">に対するアクセス許可 id がキー、機密情報および証明書。</param>
        <param name="applicationId"> プリンシパルに代わって要求を行っているクライアントのアプリケーション ID</param>
        <summary>
            AccessPolicyEntry クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ApplicationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ApplicationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry.ApplicationId" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ApplicationId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry.ApplicationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプリンシパルに代わって要求を行っているクライアントのアプリケーション ID の設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectId">
      <MemberSignature Language="C#" Value="public string ObjectId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ObjectId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry.ObjectId" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectId As String" />
      <MemberSignature Language="F#" Value="member this.ObjectId : string with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry.ObjectId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="objectId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテナーの Azure Active Directory テナントのユーザー、サービス プリンシパルまたはセキュリティ グループのオブジェクト ID を設定します。 オブジェクト ID は、アクセス ポリシーの一覧については一意である必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.Models.Permissions Permissions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.KeyVault.Fluent.Models.Permissions Permissions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry.Permissions" />
      <MemberSignature Language="VB.NET" Value="Public Property Permissions As Permissions" />
      <MemberSignature Language="F#" Value="member this.Permissions : Microsoft.Azure.Management.KeyVault.Fluent.Models.Permissions with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry.Permissions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="permissions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.Models.Permissions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはに対するアクセス許可 id がキー、機密情報および証明書を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public Guid TenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantId As Guid" />
      <MemberSignature Language="F#" Value="member this.TenantId : Guid with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、Azure Active Directory テナント ID、key vault への要求を認証するために使用する必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="accessPolicyEntry.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>