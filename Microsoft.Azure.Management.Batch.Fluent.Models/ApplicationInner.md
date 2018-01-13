<Type Name="ApplicationInner" FullName="Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner">
  <TypeSignature Language="C#" Value="public class ApplicationInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationInner" />
  <TypeSignature Language="F#" Value="type ApplicationInner = class" />
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
            Batch アカウントに、アプリケーションの情報が含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ApplicationInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationInner (string id = null, string displayName = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt; packages = null, Nullable&lt;bool&gt; allowUpdates = null, string defaultVersion = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string displayName, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt; packages, valuetype System.Nullable`1&lt;bool&gt; allowUpdates, string defaultVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional displayName As String = null, Optional packages As IList(Of ApplicationPackageInner) = null, Optional allowUpdates As Nullable(Of Boolean) = null, Optional defaultVersion As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner" Usage="new Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner (id, displayName, packages, allowUpdates, defaultVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="packages" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt;" />
        <Parameter Name="allowUpdates" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="defaultVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">アカウント内でアプリケーションを一意に識別する文字列。</param>
        <param name="displayName">アプリケーションの表示名。</param>
        <param name="packages">このアプリケーション パッケージの一覧。</param>
        <param name="allowUpdates">同じバージョン文字列を使用して、アプリケーション内でパッケージが上書きされるかどうかを示す値。</param>
        <param name="defaultVersion">クライアントは、アプリケーションを要求しますが、バージョンを指定しない場合に使用するパッケージです。</param>
        <summary>
            ApplicationInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowUpdates">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AllowUpdates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AllowUpdates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner.AllowUpdates" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowUpdates As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AllowUpdates : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner.AllowUpdates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="allowUpdates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または同じのバージョン文字列を使用して、アプリケーション内でパッケージが上書きされるかどうかを示す値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultVersion">
      <MemberSignature Language="C#" Value="public string DefaultVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner.DefaultVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultVersion As String" />
      <MemberSignature Language="F#" Value="member this.DefaultVersion : string with get, set" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner.DefaultVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="defaultVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、クライアントは、アプリケーションを要求しますが、バージョンを指定しない場合に使用するパッケージを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
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
            取得またはアプリケーションの表示名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアカウント内でアプリケーションを一意に識別する文字列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Packages">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt; Packages { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt; Packages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner.Packages" />
      <MemberSignature Language="VB.NET" Value="Public Property Packages As IList(Of ApplicationPackageInner)" />
      <MemberSignature Language="F#" Value="member this.Packages : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner.Packages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="packages")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または このアプリケーション パッケージの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>