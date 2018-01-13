<Type Name="ApplicationCreateParameters" FullName="Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters">
  <TypeSignature Language="C#" Value="public class ApplicationCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationCreateParameters" />
  <TypeSignature Language="F#" Value="type ApplicationCreateParameters = class" />
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
            アプリケーションの追加のパラメーターです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters.#ctor" />
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
            ApplicationCreateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationCreateParameters (Nullable&lt;bool&gt; allowUpdates = null, string displayName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; allowUpdates, string displayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters.#ctor(System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional allowUpdates As Nullable(Of Boolean) = null, Optional displayName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters : Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters" Usage="new Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters (allowUpdates, displayName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="allowUpdates" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="displayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="allowUpdates">同じバージョン文字列を使用して、アプリケーション内でパッケージが上書きされるかどうかを示す値。</param>
        <param name="displayName">アプリケーションの表示名。</param>
        <summary>
            ApplicationCreateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowUpdates">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AllowUpdates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AllowUpdates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters.AllowUpdates" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowUpdates As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AllowUpdates : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters.AllowUpdates" />
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
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters.DisplayName" />
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