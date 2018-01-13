<Type Name="ResourceUsageInner" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner">
  <TypeSignature Language="C#" Value="public class ResourceUsageInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceUsageInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceUsageInner" />
  <TypeSignature Language="F#" Value="type ResourceUsageInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            チェックのリソース使用状況 API の出力です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceUsageInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ResourceUsage クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceUsageInner (string resourceType = null, string unit = null, Nullable&lt;int&gt; currentValue = null, Nullable&lt;int&gt; limit = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string resourceType, string unit, valuetype System.Nullable`1&lt;int32&gt; currentValue, valuetype System.Nullable`1&lt;int32&gt; limit) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.#ctor(System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resourceType As String = null, Optional unit As String = null, Optional currentValue As Nullable(Of Integer) = null, Optional limit As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner : string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner (resourceType, unit, currentValue, limit)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="currentValue" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="limit" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="resourceType">使用法のリソースの種類。</param>
        <param name="unit">使用状況の単位です。 例: カウントします。</param>
        <param name="currentValue">リソースの種類の実際の値。</param>
        <param name="limit">リソースの種類のクォータ。</param>
        <summary>
            ResourceUsage クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentValue As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソースの種類の実際の値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Limit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.Limit" />
      <MemberSignature Language="VB.NET" Value="Public Property Limit As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Limit : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="limit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソースの種類のクォータを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用状況のリソースの種類を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用率の単位を設定します。 例: カウントします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>