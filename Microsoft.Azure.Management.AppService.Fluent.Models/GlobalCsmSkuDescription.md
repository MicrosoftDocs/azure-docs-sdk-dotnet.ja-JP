<Type Name="GlobalCsmSkuDescription" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription">
  <TypeSignature Language="C#" Value="public class GlobalCsmSkuDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GlobalCsmSkuDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class GlobalCsmSkuDescription" />
  <TypeSignature Language="F#" Value="type GlobalCsmSkuDescription = class" />
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
            グローバルの SKU の説明です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GlobalCsmSkuDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            GlobalCsmSkuDescription クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GlobalCsmSkuDescription (string name = null, string tier = null, Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity capacity = null, System.Collections.Generic.IList&lt;string&gt; locations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt; capabilities = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string tier, class Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity capacity, class System.Collections.Generic.IList`1&lt;string&gt; locations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt; capabilities) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.#ctor(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional tier As String = null, Optional capacity As SkuCapacity = null, Optional locations As IList(Of String) = null, Optional capabilities As IList(Of CapabilityInner) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription (name, tier, capacity, locations, capabilities)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="tier" Type="System.String" />
        <Parameter Name="capacity" Type="Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity" />
        <Parameter Name="locations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="capabilities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt;" />
      </Parameters>
      <Docs>
        <param name="name">SKU のリソースの名前。</param>
        <param name="tier">SKU のリソースのサービス階層。</param>
        <param name="capacity">Min、max、および SKU の既定の小数点以下桁数の値。</param>
        <param name="locations">SKU の場所です。</param>
        <param name="capabilities">SKU の機能など、トラフィック マネージャーは有効になっています。</param>
        <summary>
            GlobalCsmSkuDescription クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capabilities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt; Capabilities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt; Capabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Capabilities" />
      <MemberSignature Language="VB.NET" Value="Public Property Capabilities As IList(Of CapabilityInner)" />
      <MemberSignature Language="F#" Value="member this.Capabilities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Capabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはなどの SKU の機能を設定、トラフィック マネージャーを有効にしますか。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As SkuCapacity" />
      <MemberSignature Language="F#" Value="member this.Capacity : Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または min、max、および SKU の既定の小数点以下桁数の値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Locations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Locations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Locations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Locations" />
      <MemberSignature Language="VB.NET" Value="Public Property Locations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Locations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Locations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="locations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または SKU の場所を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または SKU のリソースの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public string Tier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Tier" />
      <MemberSignature Language="VB.NET" Value="Public Property Tier As String" />
      <MemberSignature Language="F#" Value="member this.Tier : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサービス SKU のリソースの階層を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>