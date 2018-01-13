<Type Name="SearchAnalyzerAttribute" FullName="Microsoft.Azure.Search.SearchAnalyzerAttribute">
  <TypeSignature Language="C#" Value="public class SearchAnalyzerAttribute : Attribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SearchAnalyzerAttribute extends System.Attribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.SearchAnalyzerAttribute" />
  <TypeSignature Language="VB.NET" Value="Public Class SearchAnalyzerAttribute&#xA;Inherits Attribute" />
  <TypeSignature Language="F#" Value="type SearchAnalyzerAttribute = class&#xA;    inherit Attribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Attribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Property)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            示します、<see cref="T:Microsoft.Azure.Search.Models.Field" />によって生成された<see cref="T:Microsoft.Azure.Search.FieldBuilder" />ターゲットのプロパティが含まれて、<see cref="P:Microsoft.Azure.Search.Models.Field.SearchAnalyzer" />プロパティを指定されたアナライザーに設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchAnalyzerAttribute (string analyzerName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string analyzerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SearchAnalyzerAttribute.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (analyzerName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.SearchAnalyzerAttribute : string -&gt; Microsoft.Azure.Search.SearchAnalyzerAttribute" Usage="new Microsoft.Azure.Search.SearchAnalyzerAttribute analyzerName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="analyzerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="analyzerName">
            アナライザーの名前です。 内の名前のいずれかを使用して<see cref="T:Microsoft.Azure.Search.Models.AnalyzerName.AsString" />またはカスタム アナライザーの名前。
            </param>
        <summary>
            指定されたアナライザーを使用することを示します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.SearchAnalyzerAttribute.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Search.SearchAnalyzerAttribute.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>