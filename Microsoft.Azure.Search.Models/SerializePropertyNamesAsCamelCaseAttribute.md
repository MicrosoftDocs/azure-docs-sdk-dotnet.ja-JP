<Type Name="SerializePropertyNamesAsCamelCaseAttribute" FullName="Microsoft.Azure.Search.Models.SerializePropertyNamesAsCamelCaseAttribute">
  <TypeSignature Language="C#" Value="public class SerializePropertyNamesAsCamelCaseAttribute : Attribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SerializePropertyNamesAsCamelCaseAttribute extends System.Attribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SerializePropertyNamesAsCamelCaseAttribute" />
  <TypeSignature Language="VB.NET" Value="Public Class SerializePropertyNamesAsCamelCaseAttribute&#xA;Inherits Attribute" />
  <TypeSignature Language="F#" Value="type SerializePropertyNamesAsCamelCaseAttribute = class&#xA;    inherit Attribute" />
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
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Class, AllowMultiple=false, Inherited=true)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="efda3-101">Azure Search インデックスのフィールド名を一致させるために、camel 形式でとしてモデル クラスのパブリック プロパティをシリアル化することを示します。</span><span class="sxs-lookup"><span data-stu-id="efda3-101">Indicates that the public properties of a model class should be serialized as camel-case in order to match the field names of an Azure Search index.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="efda3-102">この属性を持たないクラスは、Azure Search で対応するフィールド名と正確に一致するプロパティの名前を持つことが必要です。</span><span class="sxs-lookup"><span data-stu-id="efda3-102">Classes without this attribute are expected to have property names that exactly match their corresponding fields names in Azure Search.</span></span> <span data-ttu-id="efda3-103">それ以外の場合、いない可能性があります、インデックスを作成するクラスのインスタンスを使用します。</span><span class="sxs-lookup"><span data-stu-id="efda3-103">Otherwise, it would not be possible to use instances of the class to populate the index.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SerializePropertyNamesAsCamelCaseAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SerializePropertyNamesAsCamelCaseAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>