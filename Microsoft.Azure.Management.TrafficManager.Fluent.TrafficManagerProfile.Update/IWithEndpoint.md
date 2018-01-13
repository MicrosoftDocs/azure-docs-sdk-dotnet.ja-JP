<Type Name="IWithEndpoint" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithEndpoint">
  <TypeSignature Language="C#" Value="public interface IWithEndpoint" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithEndpoint" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithEndpoint" />
  <TypeSignature Language="F#" Value="type IWithEndpoint = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            エンドポイントの指定を許可するトラフィック マネージャー プロファイルの更新の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineAzureTargetEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IAzureTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt; DefineAzureTargetEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IAzureTargetEndpointBlank`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt; DefineAzureTargetEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithEndpoint.DefineAzureTargetEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineAzureTargetEndpoint (name As String) As IAzureTargetEndpointBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineAzureTargetEndpoint : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IAzureTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt;" Usage="iWithEndpoint.DefineAzureTargetEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IAzureTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">エンドポイントの名前です。</param>
        <summary>
            Traffic manager プロファイルにアタッチされている Azure のエンドポイントの定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>エンドポイントの構成を表す段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="DefineExternalTargetEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IExternalTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt; DefineExternalTargetEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IExternalTargetEndpointBlank`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt; DefineExternalTargetEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithEndpoint.DefineExternalTargetEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineExternalTargetEndpoint (name As String) As IExternalTargetEndpointBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineExternalTargetEndpoint : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IExternalTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt;" Usage="iWithEndpoint.DefineExternalTargetEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IExternalTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">エンドポイントの名前です。</param>
        <summary>
            Traffic manager プロファイルにアタッチされている外部エンドポイントの定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>エンドポイントの構成を表す段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="DefineNestedTargetEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.INestedProfileTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt; DefineNestedTargetEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.INestedProfileTargetEndpointBlank`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt; DefineNestedTargetEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithEndpoint.DefineNestedTargetEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNestedTargetEndpoint (name As String) As INestedProfileTargetEndpointBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNestedTargetEndpoint : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.INestedProfileTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt;" Usage="iWithEndpoint.DefineNestedTargetEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.INestedProfileTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">エンドポイントの名前です。</param>
        <summary>
            Traffic manager プロファイルにアタッチされている入れ子になったプロファイル エンドポイントの定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>エンドポイントの構成を表す段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateAzureTargetEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateAzureEndpoint.IUpdateAzureEndpoint UpdateAzureTargetEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateAzureEndpoint.IUpdateAzureEndpoint UpdateAzureTargetEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithEndpoint.UpdateAzureTargetEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAzureTargetEndpoint (name As String) As IUpdateAzureEndpoint" />
      <MemberSignature Language="F#" Value="abstract member UpdateAzureTargetEndpoint : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateAzureEndpoint.IUpdateAzureEndpoint" Usage="iWithEndpoint.UpdateAzureTargetEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateAzureEndpoint.IUpdateAzureEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Azure のエンドポイントの名前。</param>
        <summary>
            このプロファイルに既存の Azure エンドポイントの更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ステージを表す構成を更新して、Azure のエンドポイント。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateExternalTargetEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateExternalEndpoint.IUpdateExternalEndpoint UpdateExternalTargetEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateExternalEndpoint.IUpdateExternalEndpoint UpdateExternalTargetEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithEndpoint.UpdateExternalTargetEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateExternalTargetEndpoint (name As String) As IUpdateExternalEndpoint" />
      <MemberSignature Language="F#" Value="abstract member UpdateExternalTargetEndpoint : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateExternalEndpoint.IUpdateExternalEndpoint" Usage="iWithEndpoint.UpdateExternalTargetEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateExternalEndpoint.IUpdateExternalEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">外部エンドポイントの名前。</param>
        <summary>
            このプロファイルに既存の外部エンドポイントの更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>外部エンドポイントのステージを表す更新構成します。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateNestedProfileTargetEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint UpdateNestedProfileTargetEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint UpdateNestedProfileTargetEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithEndpoint.UpdateNestedProfileTargetEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateNestedProfileTargetEndpoint (name As String) As IUpdateNestedProfileEndpoint" />
      <MemberSignature Language="F#" Value="abstract member UpdateNestedProfileTargetEndpoint : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint" Usage="iWithEndpoint.UpdateNestedProfileTargetEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">入れ子になったプロファイル エンドポイントの名前。</param>
        <summary>
            このプロファイルに既存の入れ子になった traffic manager プロファイル エンドポイントの更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ステージを表す構成を更新して、入れ子になった traffic manager プロファイル エンドポイント。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithoutEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithoutEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithEndpoint.WithoutEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutEndpoint (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutEndpoint : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate" Usage="iWithEndpoint.WithoutEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">エンドポイントの名前。</param>
        <summary>
            プロファイルにエンドポイントを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>トラフィック マネージャー プロファイルの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>