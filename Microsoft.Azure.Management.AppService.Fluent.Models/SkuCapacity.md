<Type Name="SkuCapacity" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity">
  <TypeSignature Language="C#" Value="public class SkuCapacity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SkuCapacity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity" />
  <TypeSignature Language="VB.NET" Value="Public Class SkuCapacity" />
  <TypeSignature Language="F#" Value="type SkuCapacity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            App Service プランのスケールのオプションの説明です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SkuCapacity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SkuCapacity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SkuCapacity (Nullable&lt;int&gt; minimum = null, Nullable&lt;int&gt; maximum = null, Nullable&lt;int&gt; defaultProperty = null, string scaleType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; minimum, valuetype System.Nullable`1&lt;int32&gt; maximum, valuetype System.Nullable`1&lt;int32&gt; defaultProperty, string scaleType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional minimum As Nullable(Of Integer) = null, Optional maximum As Nullable(Of Integer) = null, Optional defaultProperty As Nullable(Of Integer) = null, Optional scaleType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity : Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity (minimum, maximum, defaultProperty, scaleType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minimum" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maximum" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="defaultProperty" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="scaleType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="minimum">この App Service プランの SKU のワーカーの最小数。</param>
        <param name="maximum">この App Service プランの SKU のワーカーの最大数。</param>
        <param name="defaultProperty">既定のこの App Service プランの SKU ワーカーの数。</param>
        <param name="scaleType">App Service プランの構成を使用可能なスケールします。</param>
        <summary>
            SkuCapacity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultProperty">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DefaultProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DefaultProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity.DefaultProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultProperty As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DefaultProperty : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity.DefaultProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="default")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこの App Service プランの SKU ワーカーの数を既定値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Maximum">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Maximum { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Maximum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity.Maximum" />
      <MemberSignature Language="VB.NET" Value="Public Property Maximum As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Maximum : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity.Maximum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maximum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこの App Service プランの SKU のワーカーの最大数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Minimum">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Minimum { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Minimum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity.Minimum" />
      <MemberSignature Language="VB.NET" Value="Public Property Minimum As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Minimum : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity.Minimum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minimum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこの App Service プランの SKU のワーカーの最小数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScaleType">
      <MemberSignature Language="C#" Value="public string ScaleType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScaleType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity.ScaleType" />
      <MemberSignature Language="VB.NET" Value="Public Property ScaleType As String" />
      <MemberSignature Language="F#" Value="member this.ScaleType : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity.ScaleType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scaleType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または App Service プランの利用可能なスケール構成を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>