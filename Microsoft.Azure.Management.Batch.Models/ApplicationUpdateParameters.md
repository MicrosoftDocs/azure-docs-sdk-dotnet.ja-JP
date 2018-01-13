<Type Name="ApplicationUpdateParameters" FullName="Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters">
  <TypeSignature Language="C#" Value="public class ApplicationUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationUpdateParameters" />
  <TypeSignature Language="F#" Value="type ApplicationUpdateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            アプリケーションの更新要求のパラメーターです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ApplicationUpdateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationUpdateParameters (Nullable&lt;bool&gt; allowUpdates = null, string defaultVersion = null, string displayName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; allowUpdates, string defaultVersion, string displayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters.#ctor(System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional allowUpdates As Nullable(Of Boolean) = null, Optional defaultVersion As String = null, Optional displayName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters : Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters" Usage="new Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters (allowUpdates, defaultVersion, displayName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="allowUpdates" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="defaultVersion" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="allowUpdates">同じバージョン文字列を使用して、アプリケーション内でパッケージが上書きされるかどうかを示す値。</param>
        <param name="defaultVersion">クライアントは、アプリケーションを要求しますが、バージョンを指定しない場合に使用するパッケージです。</param>
        <param name="displayName">アプリケーションの表示名。</param>
        <summary>
            ApplicationUpdateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowUpdates">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AllowUpdates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AllowUpdates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters.AllowUpdates" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowUpdates As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AllowUpdates : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters.AllowUpdates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters.DefaultVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultVersion As String" />
      <MemberSignature Language="F#" Value="member this.DefaultVersion : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters.DefaultVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
  </Members>
</Type>