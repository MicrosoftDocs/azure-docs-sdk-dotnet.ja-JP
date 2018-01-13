<Type Name="AvailableProviderOperation" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation">
  <TypeSignature Language="C#" Value="public class AvailableProviderOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AvailableProviderOperation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation" />
  <TypeSignature Language="VB.NET" Value="Public Class AvailableProviderOperation" />
  <TypeSignature Language="F#" Value="type AvailableProviderOperation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            使用可能なプロバイダーの操作を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProviderOperation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AvailableProviderOperation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProviderOperation (string name = null, Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay display = null, string origin = null, object properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay display, string origin, object properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.#ctor(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional display As AvailableProviderOperationDisplay = null, Optional origin As String = null, Optional properties As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation : string * Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay * string * obj -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation (name, display, origin, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="display" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay" />
        <Parameter Name="origin" Type="System.String" />
        <Parameter Name="properties" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="name">特定のオブジェクトで実行される操作の名前。 名の形式:"{resourceProviderNamespace}/{resourceType}/{読み取り | 書き込み | を削除 | アクション}"。
            例: Microsoft.StorSimple/managers/devices/volumeContainers/read、Microsoft.StorSimple/managers/devices/alerts/clearAlerts/action</param>
        <param name="display">この特定の操作/アクションのローカライズされた表示情報が含まれています。</param>
        <param name="origin">操作の目的の実行子RBAC UX およびエクスペリエンスは、監査ログで、操作の表示を制御します。 既定値は「ユーザー、システム」</param>
        <param name="properties">将来使用するために予約されています。</param>
        <summary>
            AvailableProviderOperation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Display">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay Display { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay Display" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.Display" />
      <MemberSignature Language="VB.NET" Value="Public Property Display As AvailableProviderOperationDisplay" />
      <MemberSignature Language="F#" Value="member this.Display : Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.Display" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="display")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定には、この特定の操作/アクションのローカライズされた表示情報が含まれています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            取得または特定のオブジェクトで実行される操作の名前を設定します。 名の形式:"{resourceProviderNamespace}/{resourceType}/{読み取り | 書き込み | を削除 | アクション}"。
            例: Microsoft.StorSimple/managers/devices/volumeContainers/read、Microsoft.StorSimple/managers/devices/alerts/clearAlerts/action
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Origin">
      <MemberSignature Language="C#" Value="public string Origin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Origin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.Origin" />
      <MemberSignature Language="VB.NET" Value="Public Property Origin As String" />
      <MemberSignature Language="F#" Value="member this.Origin : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.Origin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="origin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定操作の目的の実行子RBAC UX およびエクスペリエンスは、監査ログで、操作の表示を制御します。
            既定値は「ユーザー、システム」
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public object Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As Object" />
      <MemberSignature Language="F#" Value="member this.Properties : obj with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定将来使用するために予約されています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>