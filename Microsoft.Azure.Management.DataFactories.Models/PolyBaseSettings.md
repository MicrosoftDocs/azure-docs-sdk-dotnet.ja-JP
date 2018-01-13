<Type Name="PolyBaseSettings" FullName="Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings">
  <TypeSignature Language="C#" Value="public class PolyBaseSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PolyBaseSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class PolyBaseSettings" />
  <TypeSignature Language="F#" Value="type PolyBaseSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Polybase の設定です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolyBaseSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RejectSampleValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;ulong&gt; RejectSampleValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;unsigned int64&gt; RejectSampleValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.RejectSampleValue" />
      <MemberSignature Language="VB.NET" Value="Public Property RejectSampleValue As Nullable(Of ULong)" />
      <MemberSignature Language="F#" Value="member this.RejectSampleValue : Nullable&lt;uint64&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.RejectSampleValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.UInt64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 PolyBase が拒否された行の割合を再計算する前に取得しようとする行の数を決定します。
            RejectType はときに必要な<see cref="F:Microsoft.Azure.Management.DataFactories.Models.PolyBaseRejectType.Percentage" />します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RejectType">
      <MemberSignature Language="C#" Value="public string RejectType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RejectType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.RejectType" />
      <MemberSignature Language="VB.NET" Value="Public Property RejectType As String" />
      <MemberSignature Language="F#" Value="member this.RejectType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.RejectType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 RejectValue がリテラル値またはパーセントとして指定するかどうかを示します。
            いずれかを指定する必要があります<see cref="T:Microsoft.Azure.Management.DataFactories.Models.PolyBaseRejectType" />です。
            既定値は <see cref="F:Microsoft.Azure.Management.DataFactories.Models.PolyBaseRejectType.Value" /> です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RejectValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; RejectValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; RejectValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.RejectValue" />
      <MemberSignature Language="VB.NET" Value="Public Property RejectValue As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.RejectValue : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.RejectValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 または、クエリが失敗する前に拒否されることもの行のパーセンテージの値を指定します。
            既定値は 0 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseTypeDefault">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UseTypeDefault { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UseTypeDefault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.UseTypeDefault" />
      <MemberSignature Language="VB.NET" Value="Public Property UseTypeDefault As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UseTypeDefault : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.UseTypeDefault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 PolyBase がテキスト ファイルからデータを取得する場合にどのように区切りテキスト ファイル内の不足値を処理するかを、指定します。
            既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>