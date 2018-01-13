<Type Name="ADGroupInner" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner">
  <TypeSignature Language="C#" Value="public class ADGroupInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ADGroupInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ADGroupInner" />
  <TypeSignature Language="F#" Value="type ADGroupInner = class" />
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
            Active Directory グループの情報です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ADGroupInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ADGroupInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ADGroupInner (string objectId = null, string objectType = null, string displayName = null, Nullable&lt;bool&gt; securityEnabled = null, string mail = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string objectId, string objectType, string displayName, valuetype System.Nullable`1&lt;bool&gt; securityEnabled, string mail) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner.#ctor(System.String,System.String,System.String,System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional objectId As String = null, Optional objectType As String = null, Optional displayName As String = null, Optional securityEnabled As Nullable(Of Boolean) = null, Optional mail As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner : string * string * string * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner (objectId, objectType, displayName, securityEnabled, mail)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="objectType" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="securityEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="mail" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="objectId">オブジェクト ID。</param>
        <param name="objectType">オブジェクトの型。</param>
        <param name="displayName">グループの表示名。</param>
        <param name="securityEnabled">かどうか、グループは、セキュリティを有効にします。</param>
        <param name="mail">グループのプライマリ電子メール アドレス。</param>
        <summary>
            ADGroupInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはグループの表示名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mail">
      <MemberSignature Language="C#" Value="public string Mail { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Mail" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner.Mail" />
      <MemberSignature Language="VB.NET" Value="Public Property Mail As String" />
      <MemberSignature Language="F#" Value="member this.Mail : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner.Mail" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mail")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはグループのプライマリ電子メール アドレスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectId">
      <MemberSignature Language="C#" Value="public string ObjectId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ObjectId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner.ObjectId" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectId As String" />
      <MemberSignature Language="F#" Value="member this.ObjectId : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner.ObjectId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
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
            取得または設定オブジェクトの id です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectType">
      <MemberSignature Language="C#" Value="public string ObjectType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ObjectType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner.ObjectType" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectType As String" />
      <MemberSignature Language="F#" Value="member this.ObjectType : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner.ObjectType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="objectType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはオブジェクトの種類を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SecurityEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SecurityEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner.SecurityEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SecurityEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner.SecurityEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="securityEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはグループがセキュリティを有効にするかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>