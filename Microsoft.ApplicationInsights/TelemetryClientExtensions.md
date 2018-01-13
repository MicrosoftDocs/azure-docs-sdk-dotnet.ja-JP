<Type Name="TelemetryClientExtensions" FullName="Microsoft.ApplicationInsights.TelemetryClientExtensions">
  <TypeSignature Language="C#" Value="public static class TelemetryClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TelemetryClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.TelemetryClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TelemetryClientExtensions" />
  <TypeSignature Language="F#" Value="type TelemetryClientExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            それぞれのフィールドが初期化の操作のオブジェクトを作成する遠隔測定のクライアントに拡張クラス。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="StartOperation&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt; StartOperation&lt;T&gt; (this Microsoft.ApplicationInsights.TelemetryClient telemetryClient, string operationName) where T : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetrynew();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ApplicationInsights.Extensibility.IOperationHolder`1&lt;!!T&gt; StartOperation&lt;.ctor (class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry) T&gt;(class Microsoft.ApplicationInsights.TelemetryClient telemetryClient, string operationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation``1(Microsoft.ApplicationInsights.TelemetryClient,System.String)" />
      <MemberSignature Language="F#" Value="static member StartOperation : Microsoft.ApplicationInsights.TelemetryClient * string -&gt; Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;'T (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry and 'T : (new : unit -&gt; 'T))&gt; (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry and 'T : (new : unit -&gt; 'T))" Usage="Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation (telemetryClient, operationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <BaseTypeName>Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="telemetryClient" Type="Microsoft.ApplicationInsights.TelemetryClient" RefType="this" />
        <Parameter Name="operationName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">製品利用統計情報項目の種類。</typeparam>
        <param name="telemetryClient">遠隔測定のクライアント オブジェクトです。</param>
        <param name="operationName">名前の操作の顧客が反映されるまでを計画します。</param>
        <summary>
            開始操作は、それぞれのテレメトリ項目を操作のオブジェクトを作成します。 
            </summary>
        <returns>操作項目オブジェクトが現在を持つ新しい製品利用統計情報項目では、時間とタイムスタンプを起動します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOperation&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt; StartOperation&lt;T&gt; (this Microsoft.ApplicationInsights.TelemetryClient telemetryClient, T operationTelemetry) where T : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ApplicationInsights.Extensibility.IOperationHolder`1&lt;!!T&gt; StartOperation&lt;(class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry) T&gt;(class Microsoft.ApplicationInsights.TelemetryClient telemetryClient, !!T operationTelemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation``1(Microsoft.ApplicationInsights.TelemetryClient,``0)" />
      <MemberSignature Language="F#" Value="static member StartOperation : Microsoft.ApplicationInsights.TelemetryClient * 'T -&gt; Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;'T (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry)&gt; (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry)" Usage="Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation (telemetryClient, operationTelemetry)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <BaseTypeName>Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="telemetryClient" Type="Microsoft.ApplicationInsights.TelemetryClient" RefType="this" />
        <Parameter Name="operationTelemetry" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">製品利用統計情報項目の種類。</typeparam>
        <param name="telemetryClient">遠隔測定のクライアント オブジェクトです。</param>
        <param name="operationTelemetry">起動する操作です。</param>
        <summary>
            特定のテレメトリ項目を操作のオブジェクトを作成します。 
            </summary>
        <returns>操作項目オブジェクトが現在を持つ新しい製品利用統計情報項目では、時間とタイムスタンプを起動します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOperation&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt; StartOperation&lt;T&gt; (this Microsoft.ApplicationInsights.TelemetryClient telemetryClient, string operationName, string operationId, string parentOperationId = null) where T : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetrynew();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ApplicationInsights.Extensibility.IOperationHolder`1&lt;!!T&gt; StartOperation&lt;.ctor (class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry) T&gt;(class Microsoft.ApplicationInsights.TelemetryClient telemetryClient, string operationName, string operationId, string parentOperationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation``1(Microsoft.ApplicationInsights.TelemetryClient,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member StartOperation : Microsoft.ApplicationInsights.TelemetryClient * string * string * string -&gt; Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;'T (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry and 'T : (new : unit -&gt; 'T))&gt; (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry and 'T : (new : unit -&gt; 'T))" Usage="Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation (telemetryClient, operationName, operationId, parentOperationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <BaseTypeName>Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="telemetryClient" Type="Microsoft.ApplicationInsights.TelemetryClient" RefType="this" />
        <Parameter Name="operationName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="parentOperationId" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">製品利用統計情報項目の種類。</typeparam>
        <param name="telemetryClient">遠隔測定のクライアント オブジェクトです。</param>
        <param name="operationName">名前の操作の顧客が反映されるまでを計画します。</param>
        <param name="operationId">新しい操作を設定する操作 ID。</param>
        <param name="parentOperationId">新しい操作で設定する省略可能な親操作 ID です。</param>
        <summary>
            開始操作は、それぞれのテレメトリ項目を操作のオブジェクトを作成します。 
            </summary>
        <returns>操作項目オブジェクトが現在を持つ新しい製品利用統計情報項目では、時間とタイムスタンプを起動します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopOperation&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static void StopOperation&lt;T&gt; (this Microsoft.ApplicationInsights.TelemetryClient telemetryClient, Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt; operation) where T : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void StopOperation&lt;(class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry) T&gt;(class Microsoft.ApplicationInsights.TelemetryClient telemetryClient, class Microsoft.ApplicationInsights.Extensibility.IOperationHolder`1&lt;!!T&gt; operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClientExtensions.StopOperation``1(Microsoft.ApplicationInsights.TelemetryClient,Microsoft.ApplicationInsights.Extensibility.IOperationHolder{``0})" />
      <MemberSignature Language="F#" Value="static member StopOperation : Microsoft.ApplicationInsights.TelemetryClient * Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;'T (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry)&gt; -&gt; unit (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry)" Usage="Microsoft.ApplicationInsights.TelemetryClientExtensions.StopOperation (telemetryClient, operation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <BaseTypeName>Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="telemetryClient" Type="Microsoft.ApplicationInsights.TelemetryClient" RefType="this" />
        <Parameter Name="operation" Type="Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="telemetryClient">遠隔測定のクライアント オブジェクトです。</param>
        <param name="operation">期間と履歴を計算する操作のオブジェクト。</param>
        <summary>
            停止操作は、操作の間を計算し、それぞれの遠隔測定のクライアントを使用してそれを追跡します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>