<Type Name="GetPropertyOperation" FullName="System.Fabric.GetPropertyOperation">
  <TypeSignature Language="C#" Value="public sealed class GetPropertyOperation : System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit GetPropertyOperation extends System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.GetPropertyOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class GetPropertyOperation&#xA;Inherits PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type GetPropertyOperation = class&#xA;    inherit PropertyBatchOperation" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.PropertyBatchOperation</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>表す、<see cref="T:System.Fabric.PropertyBatchOperation" />にある場合、指定したプロパティを取得します。</para>
    </summary>
    <remarks>
      <para>注意してください。 1 つ<see cref="T:System.Fabric.PropertyBatchOperation" />失敗バッチ全体が失敗し、コミットできません。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GetPropertyOperation (string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.GetPropertyOperation.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.GetPropertyOperation : string -&gt; System.Fabric.GetPropertyOperation" Usage="new System.Fabric.GetPropertyOperation propertyName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>プロパティの名前。</para>
        </param>
        <summary>
          <para>新しいインスタンスをインスタンス化、<see cref="T:System.Fabric.GetPropertyOperation" />指定したプロパティ名を持つクラス。</para>
        </summary>
        <remarks>
          <para>
            <see cref="P:System.Fabric.GetPropertyOperation.IncludeValue" />設定されている<languageKeyword>true</languageKeyword>です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GetPropertyOperation (string propertyName, bool includeValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, bool includeValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.GetPropertyOperation.#ctor(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, includeValue As Boolean)" />
      <MemberSignature Language="F#" Value="new System.Fabric.GetPropertyOperation : string * bool -&gt; System.Fabric.GetPropertyOperation" Usage="new System.Fabric.GetPropertyOperation (propertyName, includeValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="includeValue" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>プロパティの名前。</para>
        </param>
        <param name="includeValue">
          <para>戻り値に値を含める必要がありますまたはメタデータのみを返す必要があるかどうかを指定します。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、 <see cref="T:System.Fabric.GetPropertyOperation" /> with プロパティ名を指定し、値のフラグが含まれています。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeValue">
      <MemberSignature Language="C#" Value="public bool IncludeValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IncludeValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.GetPropertyOperation.IncludeValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IncludeValue As Boolean" />
      <MemberSignature Language="F#" Value="member this.IncludeValue : bool" Usage="System.Fabric.GetPropertyOperation.IncludeValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>プロパティの値が、メタデータと共に返されるかどうかを示す値を取得します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>プロパティの値を含める必要がある場合<languageKeyword>false</languageKeyword>それ以外の場合。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>