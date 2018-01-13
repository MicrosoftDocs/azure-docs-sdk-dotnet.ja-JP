<Type Name="IPAddressOrRange" FullName="Microsoft.WindowsAzure.Storage.IPAddressOrRange">
  <TypeSignature Language="C#" Value="public class IPAddressOrRange" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IPAddressOrRange extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.IPAddressOrRange" />
  <TypeSignature Language="VB.NET" Value="Public Class IPAddressOrRange" />
  <TypeSignature Language="F#" Value="type IPAddressOrRange = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            単一の IP アドレスまたは単一の IP アドレス範囲 (、最小、最大、包括的です。) のいずれかを指定します
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IPAddressOrRange (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.IPAddressOrRange.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.IPAddressOrRange : string -&gt; Microsoft.WindowsAzure.Storage.IPAddressOrRange" Usage="new Microsoft.WindowsAzure.Storage.IPAddressOrRange address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address">IPAddressOrRange オブジェクトを表す IP アドレス。</param>
        <summary>
            1 つの ip アドレスから IPAddressOrRange クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IPAddressOrRange (string minimum, string maximum);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string minimum, string maximum) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.IPAddressOrRange.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (minimum As String, maximum As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.IPAddressOrRange : string * string -&gt; Microsoft.WindowsAzure.Storage.IPAddressOrRange" Usage="new Microsoft.WindowsAzure.Storage.IPAddressOrRange (minimum, maximum)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minimum" Type="System.String" />
        <Parameter Name="maximum" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="minimum">IPAddressOrRange オブジェクトは包括的な範囲の境界として使用する最小の IP アドレス。</param>
        <param name="maximum">IPAddressOrRange オブジェクトは包括的な範囲の境界として使用する最大 IP アドレス。</param>
        <summary>
            2 つの ip アドレスのオブジェクト、最小および最大から IPAddressOrRange クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public string Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IPAddressOrRange.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As String" />
      <MemberSignature Language="F#" Value="member this.Address : string" Usage="Microsoft.WindowsAzure.Storage.IPAddressOrRange.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IP アドレス。
            このオブジェクトは、IP アドレスの範囲を表している場合は null を返します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSingleAddress">
      <MemberSignature Language="C#" Value="public bool IsSingleAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSingleAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IPAddressOrRange.IsSingleAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSingleAddress As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSingleAddress : bool" Usage="Microsoft.WindowsAzure.Storage.IPAddressOrRange.IsSingleAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            True の場合は、このオブジェクトは、単一の IP アドレス範囲を表す場合は false を表します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumAddress">
      <MemberSignature Language="C#" Value="public string MaximumAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaximumAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IPAddressOrRange.MaximumAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumAddress As String" />
      <MemberSignature Language="F#" Value="member this.MaximumAddress : string" Usage="Microsoft.WindowsAzure.Storage.IPAddressOrRange.MaximumAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            包括的に、範囲の最大の IP アドレス。
            返します。 この場合は、null オブジェクトでは、単一の IP アドレスを表します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumAddress">
      <MemberSignature Language="C#" Value="public string MinimumAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MinimumAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IPAddressOrRange.MinimumAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinimumAddress As String" />
      <MemberSignature Language="F#" Value="member this.MinimumAddress : string" Usage="Microsoft.WindowsAzure.Storage.IPAddressOrRange.MinimumAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            包括的に、範囲の最小の IP アドレス。
            返します。 この場合は、null オブジェクトでは、単一の IP アドレスを表します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.IPAddressOrRange.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="iPAddressOrRange.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            この IPAddressOrRange オブジェクトの文字列表現を提供します。
            </summary>
        <returns>この IPAddressOrRange オブジェクトの文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>