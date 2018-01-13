<Type Name="ResourceNameAvailability" FullName="Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability">
  <TypeSignature Language="C#" Value="public class ResourceNameAvailability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceNameAvailability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceNameAvailability" />
  <TypeSignature Language="F#" Value="type ResourceNameAvailability = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            リソース名の可用性に関する情報です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceNameAvailability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ResourceNameAvailability クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceNameAvailability (Nullable&lt;bool&gt; nameAvailable = null, string reason = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; nameAvailable, string reason, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability.#ctor(System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nameAvailable As Nullable(Of Boolean) = null, Optional reason As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability : Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability" Usage="new Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability (nameAvailable, reason, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nameAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="reason" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nameAvailable">&lt;コード&gt;true&lt;/code&gt;名が有効であり、使用可能なことを示します。 &lt;コード&gt;false&lt;/code&gt;名前が無効な使用できなくなったことを示しますまたはその両方です。</param>
        <param name="reason">&lt;コード&gt;無効な&lt;/code&gt;示す指定された名前は、Azure App Service の名前付けに関する要件と一致しません。
            &lt;コード&gt;に対する&lt;/code&gt;名前は既に使用され、にないため、使用可能なことを示します。 使用可能な値が含まれます: '無効'、'に対する'</param>
        <param name="message">場合の理由が無効です、= = 指定された名前が有効でない理由をユーザーに提供し、名前付けに関する要件をユーザーが有効な名前を選択できるように、リソースを提供します。 場合の理由 = = されて、そのリソース名は既に使用、について説明し、別の名前を選択するように指示します。</param>
        <summary>
            ResourceNameAvailability クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の場合は理由 = = 無効な場合は、指定された名前が有効でない理由をユーザーに提供し、名前付けに関する要件をユーザーが有効な名前を選択できるように、リソースを提供します。 場合の理由 = = されて、そのリソース名は既に使用、について説明し、別の名前を選択するように指示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; NameAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; NameAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability.NameAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property NameAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NameAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability.NameAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nameAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt; 名前が有効であり、使用可能なことを示します。
            &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;、名前は、無効な使用できなくなったことを示しますまたはその両方です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability.Reason" />
      <MemberSignature Language="VB.NET" Value="Public Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt; 無効な&amp;lt;/code&amp;gt; 指定された名前は、Azure App Service の名前付けに関する要件と一致しませんを示します。
            &amp;lt; コード&amp;gt;に対する&amp;lt;/code&amp;gt;、名前は既に使用され、にないため、使用可能なことを示します。
            使用可能な値が含まれます: '無効'、'に対する'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>