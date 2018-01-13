<Type Name="TimeSettings" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.TimeSettings">
  <TypeSignature Language="C#" Value="public class TimeSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TimeSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.TimeSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class TimeSettings" />
  <TypeSignature Language="F#" Value="type TimeSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            デバイスの時刻の設定
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TimeSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.TimeSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            TimeSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TimeSettings (string primary, string timeZone);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string primary, string timeZone) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.TimeSettings.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (primary As String, timeZone As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.Models.TimeSettings : string * string -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TimeSettings" Usage="new Microsoft.WindowsAzure.Management.StorSimple.Models.TimeSettings (primary, timeZone)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primary" Type="System.String" />
        <Parameter Name="timeZone" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="primary">To be added.</param>
        <param name="timeZone">To be added.</param>
        <summary>
            必須の引数で TimeSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Primary">
      <MemberSignature Language="C#" Value="public string Primary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Primary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TimeSettings.Primary" />
      <MemberSignature Language="VB.NET" Value="Public Property Primary As String" />
      <MemberSignature Language="F#" Value="member this.Primary : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TimeSettings.Primary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 取得または設定時のプライマリ サーバー
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Secondary">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Secondary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Secondary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TimeSettings.Secondary" />
      <MemberSignature Language="VB.NET" Value="Public Property Secondary As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Secondary : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TimeSettings.Secondary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 取得またはセカンダリ タイム サーバーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeZone">
      <MemberSignature Language="C#" Value="public string TimeZone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeZone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TimeSettings.TimeZone" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeZone As String" />
      <MemberSignature Language="F#" Value="member this.TimeZone : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TimeSettings.TimeZone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 取得またはタイム ゾーンの設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>