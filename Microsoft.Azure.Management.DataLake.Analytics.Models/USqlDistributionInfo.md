<Type Name="USqlDistributionInfo" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo">
  <TypeSignature Language="C#" Value="public class USqlDistributionInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlDistributionInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlDistributionInfo" />
  <TypeSignature Language="F#" Value="type USqlDistributionInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Data Lake Analytics カタログ U-SQL 配布情報オブジェクトです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlDistributionInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            USqlDistributionInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlDistributionInfo (Nullable&lt;int&gt; type = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; keys = null, Nullable&lt;int&gt; count = null, Nullable&lt;int&gt; dynamicCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; type, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; keys, valuetype System.Nullable`1&lt;int32&gt; count, valuetype System.Nullable`1&lt;int32&gt; dynamicCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.#ctor(System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn},System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional type As Nullable(Of Integer) = null, Optional keys As IList(Of USqlDirectedColumn) = null, Optional count As Nullable(Of Integer) = null, Optional dynamicCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo : Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo (type, keys, count, dynamicCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="keys" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="dynamicCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="type">この配布の種類。</param>
        <param name="keys">分布の有向列の一覧</param>
        <param name="count">この配布を使用する、インデックスの数。</param>
        <param name="dynamicCount">この配布を使用する、インデックスの動的数。</param>
        <summary>
            USqlDistributionInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この配布を使用する、インデックスの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DynamicCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DynamicCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DynamicCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.DynamicCount" />
      <MemberSignature Language="VB.NET" Value="Public Property DynamicCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DynamicCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.DynamicCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dynamicCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この配布を使用する、インデックスの動的な数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Keys">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; Keys { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; Keys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.Keys" />
      <MemberSignature Language="VB.NET" Value="Public Property Keys As IList(Of USqlDirectedColumn)" />
      <MemberSignature Language="F#" Value="member this.Keys : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.Keys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または分布の有向列の一覧を設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Type : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこの分布の種類を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>