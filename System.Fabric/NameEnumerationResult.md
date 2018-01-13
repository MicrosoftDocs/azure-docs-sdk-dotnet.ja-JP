<Type Name="NameEnumerationResult" FullName="System.Fabric.NameEnumerationResult">
  <TypeSignature Language="C#" Value="public class NameEnumerationResult : System.Collections.ObjectModel.Collection&lt;Uri&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NameEnumerationResult extends System.Collections.ObjectModel.Collection`1&lt;class System.Uri&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NameEnumerationResult" />
  <TypeSignature Language="VB.NET" Value="Public Class NameEnumerationResult&#xA;Inherits Collection(Of Uri)" />
  <TypeSignature Language="F#" Value="type NameEnumerationResult = class&#xA;    inherit Collection&lt;Uri&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.ObjectModel.Collection&lt;System.Uri&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.Uri</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Service Fabric のコレクションの名前、によって返される<see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumerateSubNamesAsync(System.Uri,System.Fabric.NameEnumerationResult,System.Boolean)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HasMoreData">
      <MemberSignature Language="C#" Value="public bool HasMoreData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasMoreData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NameEnumerationResult.HasMoreData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasMoreData As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasMoreData : bool" Usage="System.Fabric.NameEnumerationResult.HasMoreData" />
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
          <para>複数の残りのページがあるかどうかを示します。 場合は、値が true の場合、<see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumerateSubNamesAsync(System.Uri,System.Fabric.NameEnumerationResult,System.Boolean)" />次のページの取得を呼び出すことができます。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>場合は、列挙より多くのデータです。<languageKeyword>false</languageKeyword>それ以外の場合。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBestEffort">
      <MemberSignature Language="C#" Value="public bool IsBestEffort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBestEffort" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NameEnumerationResult.IsBestEffort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBestEffort As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBestEffort : bool" Usage="System.Fabric.NameEnumerationResult.IsBestEffort" />
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
          <para>指定した名前の下にある任意の名前が、列挙中に変更されたかどうかを示します。 変更があった場合はこのプロパティの値は true です。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>場合は、列挙体は、ベスト エフォートです。<languageKeyword>false</languageKeyword>それ以外の場合。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsConsistent">
      <MemberSignature Language="C#" Value="public bool IsConsistent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsConsistent" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NameEnumerationResult.IsConsistent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsConsistent As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsConsistent : bool" Usage="System.Fabric.NameEnumerationResult.IsConsistent" />
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
          <para>指定した名前の下にある任意の名前が、列挙中に変更されたかどうかを示します。 変更があった場合は、このプロパティの値は false です。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>場合は、列挙子は矛盾しています。<languageKeyword>false</languageKeyword>それ以外の場合。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsFinished">
      <MemberSignature Language="C#" Value="public bool IsFinished { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsFinished" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NameEnumerationResult.IsFinished" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsFinished As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsFinished : bool" Usage="System.Fabric.NameEnumerationResult.IsFinished" />
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
          <para>これ以上の残りのページがあるかどうかを示します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>列挙体が終了した; 場合<languageKeyword>false</languageKeyword>それ以外の場合。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsValid">
      <MemberSignature Language="C#" Value="public bool IsValid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsValid" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NameEnumerationResult.IsValid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsValid As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsValid : bool" Usage="System.Fabric.NameEnumerationResult.IsValid" />
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
          <para>列挙結果が有効かどうかを示します。 有効でない場合、結果を使用しません。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>列挙結果が無効である場合<languageKeyword>false</languageKeyword>それ以外の場合。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>