<Type Name="X509Name" FullName="System.Fabric.X509Name">
  <TypeSignature Language="C#" Value="public class X509Name" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit X509Name extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.X509Name" />
  <TypeSignature Language="VB.NET" Value="Public Class X509Name" />
  <TypeSignature Language="F#" Value="type X509Name = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>サブジェクトの共通名または DNS 名と証明書の X509 を識別する型</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public X509Name (string name, string issuerCertThumbprint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string issuerCertThumbprint) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.X509Name.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, issuerCertThumbprint As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.X509Name : string * string -&gt; System.Fabric.X509Name" Usage="new System.Fabric.X509Name (name, issuerCertThumbprint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="issuerCertThumbprint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>サブジェクトの共通名または DNS 名の X509 証明書</para>
        </param>
        <param name="issuerCertThumbprint">
          <para>発行者を識別する証明書の拇印</para>
        </param>
        <summary>
          <para>X509 を識別する X509Name オブジェクトを作成する証明書</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (System.Fabric.X509Name other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Equals(class System.Fabric.X509Name other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.X509Name.Equals(System.Fabric.X509Name)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As X509Name) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : System.Fabric.X509Name -&gt; bool" Usage="x509Name.Equals other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.X509Name" />
      </Parameters>
      <Docs>
        <param name="other">
          <para>現在のオブジェクトと比較するオブジェクト</para>
        </param>
        <summary>
          <para>指定したオブジェクトが現在のオブジェクトと等しいかどうかを決定します。</para>
        </summary>
        <returns>
          <para>オブジェクトが等しい場合は false それ以外の場合は true を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.X509Name.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="x509Name.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">
          <para>現在のオブジェクトと比較するオブジェクト</para>
        </param>
        <summary>
          <para>指定したオブジェクトが現在のオブジェクトと等しいかどうかを決定します。</para>
        </summary>
        <returns>
          <para>オブジェクトが等しい場合は false それ以外の場合は true を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.X509Name.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="x509Name.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>ハッシュ コードを計算します。</para>
        </summary>
        <returns>
          <para>返します<see cref="T:System.Int32" />ハッシュ コードを表すです。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssuerCertThumbprint">
      <MemberSignature Language="C#" Value="public string IssuerCertThumbprint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IssuerCertThumbprint" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Name.IssuerCertThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IssuerCertThumbprint As String" />
      <MemberSignature Language="F#" Value="member this.IssuerCertThumbprint : string" Usage="System.Fabric.X509Name.IssuerCertThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>発行者を識別する証明書のサムプリントを取得します。</para>
        </summary>
        <value>
          <para>発行者を識別する証明書の拇印</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Name.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.X509Name.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サブジェクトの共通名または X509 の DNS 名を取得する証明書</para>
        </summary>
        <value>
          <para>サブジェクトの共通名または DNS 名の X509 証明書</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>