<Type Name="AdditionalUnattendContent" FullName="Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent">
  <TypeSignature Language="C#" Value="public class AdditionalUnattendContent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdditionalUnattendContent extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent" />
  <TypeSignature Language="VB.NET" Value="Public Class AdditionalUnattendContent" />
  <TypeSignature Language="F#" Value="type AdditionalUnattendContent = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Windows セットアップで使用される、Unattend.xml ファイルに含めることができるその他の XML 形式の情報を指定します。 内容は、名前、コンポーネント名、およびコンテンツが適用されているパスを設定して定義されます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdditionalUnattendContent ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AdditionalUnattendContent クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdditionalUnattendContent (Nullable&lt;Microsoft.Azure.Management.Compute.Models.PassNames&gt; passName = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.ComponentNames&gt; componentName = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.SettingNames&gt; settingName = null, string content = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.PassNames&gt; passName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ComponentNames&gt; componentName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.SettingNames&gt; settingName, string content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.#ctor(System.Nullable{Microsoft.Azure.Management.Compute.Models.PassNames},System.Nullable{Microsoft.Azure.Management.Compute.Models.ComponentNames},System.Nullable{Microsoft.Azure.Management.Compute.Models.SettingNames},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional passName As Nullable(Of PassNames) = null, Optional componentName As Nullable(Of ComponentNames) = null, Optional settingName As Nullable(Of SettingNames) = null, Optional content As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent : Nullable&lt;Microsoft.Azure.Management.Compute.Models.PassNames&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Models.ComponentNames&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Models.SettingNames&gt; * string -&gt; Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent" Usage="new Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent (passName, componentName, settingName, content)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="passName" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.PassNames&gt;" />
        <Parameter Name="componentName" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ComponentNames&gt;" />
        <Parameter Name="settingName" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.SettingNames&gt;" />
        <Parameter Name="content" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="passName">パスの名前。 現時点では、可能な値は、OobeSystem です。 使用可能な値が含まれます: 'OobeSystem'</param>
        <param name="componentName">コンポーネントの名前。 現時点では、可能な値は、Microsoft Windows シェル セットアップです。 使用可能な値が含まれます: ' Microsoft の Windows のシェルのセットアップ '</param>
        <param name="settingName">設定の名前を指定するコンテンツが適用されます。 指定できる値は: FirstLogonCommands と AutoLogon。 使用可能な値が含まれます '自動'、'FirstLogonCommands'。</param>
        <param name="content">指定されたパスおよびコンポーネントの unattend.xml ファイルに追加される XML 形式のコンテンツを指定します。 XML では、4 KB 未満である必要があり、設定または挿入している機能のルート要素を含める必要があります。</param>
        <summary>
            AdditionalUnattendContent クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComponentName">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.ComponentNames&gt; ComponentName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ComponentNames&gt; ComponentName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.ComponentName" />
      <MemberSignature Language="VB.NET" Value="Public Property ComponentName As Nullable(Of ComponentNames)" />
      <MemberSignature Language="F#" Value="member this.ComponentName : Nullable&lt;Microsoft.Azure.Management.Compute.Models.ComponentNames&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.ComponentName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="componentName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ComponentNames&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンポーネントの名前を設定します。 現時点では、可能な値は、Microsoft Windows シェル セットアップです。 使用可能な値が含まれます: ' Microsoft の Windows のシェルのセットアップ '
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Content">
      <MemberSignature Language="C#" Value="public string Content { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Content" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.Content" />
      <MemberSignature Language="VB.NET" Value="Public Property Content As String" />
      <MemberSignature Language="F#" Value="member this.Content : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.Content" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="content")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、指定されたパスおよびコンポーネントの unattend.xml ファイルに追加される XML 形式のコンテンツを指定します。 XML では、4 KB 未満である必要があり、設定または挿入している機能のルート要素を含める必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PassName">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.PassNames&gt; PassName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.PassNames&gt; PassName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.PassName" />
      <MemberSignature Language="VB.NET" Value="Public Property PassName As Nullable(Of PassNames)" />
      <MemberSignature Language="F#" Value="member this.PassName : Nullable&lt;Microsoft.Azure.Management.Compute.Models.PassNames&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.PassName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="passName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.PassNames&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはパスの名前を設定します。 現時点では、可能な値は、OobeSystem です。 使用可能な値が含まれます: 'OobeSystem'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SettingName">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.SettingNames&gt; SettingName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.SettingNames&gt; SettingName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.SettingName" />
      <MemberSignature Language="VB.NET" Value="Public Property SettingName As Nullable(Of SettingNames)" />
      <MemberSignature Language="F#" Value="member this.SettingName : Nullable&lt;Microsoft.Azure.Management.Compute.Models.SettingNames&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.SettingName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="settingName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.SettingNames&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定が、設定の名前を指定するコンテンツが適用されます。 指定できる値は: FirstLogonCommands と AutoLogon。
            使用可能な値が含まれます '自動'、'FirstLogonCommands'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>